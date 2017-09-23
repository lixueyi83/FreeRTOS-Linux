FreeRTOS simulator for POSIX (Linux, OS X and maybe other POSIX OS)

Based on the Linux simulator originally developed by William Davy for FreeRTOS v5.3, 
the goal of this work is to keep FreeRTOS POSIX simulator in a clean seperate package 
and up to date with the latest FreeRTOS releases (v9.0.0 currently).

Directory description
----------------------
- source: FreeRTOS kernel and POSIX simulator source files
- proj: the project directory that includes main() and FreeRTOS settings for the POSIX port
- demo: demo tasks from the official FreeRTOS release



Issue Fix:
1. fatal error: sys/cdefs.h
    $ sudo apt-get install g++-multilib
