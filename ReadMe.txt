Name: Kamal Acharya
Email: acharya.24@wright.edu

Project Directory contains the following files as listed by command ls -l
total 1272
-rw-rw-r-- 1 kamal kamal   1187 Feb 19 18:28 answers.txt
-rw------- 1 kamal kamal   2902 Apr  2  2007 bitvector.cpp
-rw-rw-r-- 1 kamal kamal  25976 Feb 23 00:39 bitvector.o
-rw-rw-r-- 1 kamal kamal 302566 Feb 14 08:59 cmdsTried.txt
-rw------- 1 kamal kamal  65536 Feb 27 08:26 D1.dsk
-rw------- 1 kamal kamal 262144 Feb 27 08:26 D2.dsk
-rw------- 1 kamal kamal   5352 Oct 30  2020 directory.cpp
-rw-rw-r-- 1 kamal kamal  33552 Feb 23 00:39 directory.o
-rw------- 1 kamal kamal    174 Apr  2  2007 diskParams.dat
-rwxrwxr-x 1 kamal kamal    216 Feb 27 08:16 est
-rw------- 1 kamal kamal   4199 Apr  2  2007 file.cpp
-rw-rw-r-- 1 kamal kamal  28952 Feb 23 00:39 file.o
-rw------- 1 kamal kamal   7022 Feb 23 00:38 fs33types.hpp
-rw-rw-r-- 1 kamal kamal  63970 Feb 19 21:38 gdbSession.txt
-rw------- 1 kamal kamal   7569 Apr  2  2007 inodes.cpp
-rw-rw-r-- 1 kamal kamal  35200 Feb 23 00:39 inodes.o
-rw------- 1 kamal kamal    722 Jul  7  2020 Makefile
-rw------- 1 kamal kamal   3641 Apr  2  2007 mount.cpp
-rw-rw-r-- 1 kamal kamal  33288 Feb 23 00:39 mount.o
-rwxrwxr-x 1 kamal kamal 157200 Feb 27 08:22 P0
-rw-rw-r-- 1 kamal kamal   2733 Feb 27 08:26 ReadMe.txt
-rw------- 1 kamal kamal  15757 Feb 27 08:22 shell.cpp
-rw------- 1 kamal kamal   9044 Oct 29  2020 shell.cpp~
-rw-rw-r-- 1 kamal kamal  70448 Feb 27 08:22 shell.o
-rw------- 1 kamal kamal   3780 Apr  2  2007 simdisk.cpp
-rw-rw-r-- 1 kamal kamal  30072 Feb 23 00:39 simdisk.o
-rwxrwxr-x 1 kamal kamal    216 Feb 27 08:26 test
-rwxrwxr-x 1 kamal kamal     52 Feb 27 08:26 test2
-rw-rw-r-- 1 kamal kamal    156 Feb 27 08:25 TestScript.txt
-rw-r--r-- 1 kamal kamal   2718 Sep 24  2020 typescript
-rw------- 1 kamal kamal    112 Apr  2  2007 user.cpp
-rw------- 1 kamal kamal   6808 Apr  2  2007 volume.cpp
-rw-rw-r-- 1 kamal kamal  37120 Feb 23 00:39 volume.o



As I was new to operating system and progrmming in unix process, it was tough task for me. I have gone through
number of youtube channels that guide me alot. And ofcourse I repeatly watch the class lecture in which our professor
has given the description. As of now my shell has following features:
1. It can successfully handle the redirection even for the commands having arguments
2. Piping is implemented successfully for up to three commands using two pipes
3. Background execution is also implemented.

Problems:
1. In piping only upto three commands are supported
2. Piping,redirection or background execution all are not supported in single command.

I have demonstrated all the above features through the TestScript.txt file which contains the various commands that can
be used to test the shell and its robustness.
