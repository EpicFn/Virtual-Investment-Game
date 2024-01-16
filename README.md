#	Compiler : visual studio 2022 recently version (using x64)
# OS : Window

# Source Code 
1) gameManager.cpp
2) informationManager.cpp
3) information.cpp
4) Loan_Manager.cpp
5) player.cpp
6) portfolio.cpp
7) stockManager.cpp
8) stock.cpp
9) Window.cpp
10) Print.cpp
11) Button.cpp
12) Graph.cpp
12) main.cpp

# Header file
1) gameManager.h
2) informationManager.h
3) information.h
4) Loan_Manager.h
5) player.h
6) portfolio.h
7) stockManager.h
8) stock.h
9) Window.h
10) Print.h
11) Button.h
12) Graph.h

# TXT files
1) A_bio.txt
2) B_bio.txt
3) A_food.txt
4) B_food.txt
5) A_tech.txt
6) B_tech.txt
7) thema1.txt
8) thema2.txt
9) thema3.txt

# etc
tuffy.ttf


# Download and set SFML library
1)	Download SFML at https://www.sfml-dev.org/download/sfml/2.6.1/ (Visual C++ 17 (2022) - 64-bit version).
2)	Unzip the folder at certain directory.
3)	Create a project on Visual studio, and make a c++ file(ex) main.cpp).
4)	Open ‘프로젝트 -> (프로젝트 이름) 속성’
--------------------------------------------------------------------------------------------------------------------------------------
(1)	choose ‘모든 구성’

![image](https://github.com/EpicFn/Virtual-Investment-Game/assets/71928299/b367aebd-2d78-4c05-a91d-343ffe672eba)

(2)	Put the directory address of ‘include’ folder of SFML at ‘구성 속성 -> C/C++ -> 일반 -> 추가 포함 디렉터리’.
![image](https://github.com/EpicFn/Virtual-Investment-Game/assets/71928299/7825f28b-b3d3-4bcf-9f7a-874964b9a05b)

(3)	Put the directory address of ‘lib’ folder of SFML at ‘구성 속성 -> 링커 -> 일반 -> 추가 라이브러리 디렉터리’.
![image](https://github.com/EpicFn/Virtual-Investment-Game/assets/71928299/dc33090c-7a70-4c29-85ce-6f97067ac2aa)

(4)	Paste “sfml-main-d.lib;sfml-graphics-d.lib;sfml-window-d.lib;sfml-system-d.lib;sfml-audio-d.lib;sfml-network-d.lib” at ‘구성 속성 -> 링커 -> 입력 -> 추가 종속성’.
![image](https://github.com/EpicFn/Virtual-Investment-Game/assets/71928299/7ee102f5-ffb6-45d9-96b5-d0d08a651071)

--------------------------------------------------------------------------------------------------------------------------

5)	Move ‘.dll’ files which is in the ‘bin’ folder of SFML into the Visual Studio project folder.
![image](https://github.com/EpicFn/Virtual-Investment-Game/assets/71928299/0a2db9ca-c4df-47f5-84fa-29919e8d8cfe)

7)	Include all the ‘.dll’ files in the project. Then, you’re ready to run the game.
![image](https://github.com/EpicFn/Virtual-Investment-Game/assets/71928299/88cf8136-1248-4f66-9584-66e5ad775340)


After completing the above steps, place all the text files in the folder where the code is executed.
After placing the files into source files and header files, simply click ‘run’ to execute.
