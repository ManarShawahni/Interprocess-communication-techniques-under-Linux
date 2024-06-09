# Interprocess-communication-techniques-under-Linux

<p align="center">
<img src="https://github.com/ManarShawahni/Interprocess-communication-techniques-under-Linux/assets/137074063/d8bf12ac-ad34-4671-9515-b481cee34e38">
</p>


## Overview

This project simulates the distribution of wheat flour aid bags in northern Gaza using a multi-processing application under Linux. So that the simulation involves cargo planes parachuting wheat flour containers, relief workers collecting, splitting, and distributing these containers, and occupation forces attempting to disrupt the operation.

## Objectives

- Simulate the behavior of a wheat flour distribution operation.
- Ensure collision avoidance between cargo planes.
- Model the impact of missile attacks on containers.
- Manage relief workers' tasks and risks associated with their operations.
- Track starvation levels of families and prioritize aid distribution.

https://github.com/ManarShawahni/Interprocess-communication-techniques-under-Linux/assets/137074063/bbbdb6e3-c520-4981-afd2-6240e8f2a558
  
## languauge Used

- C (for the main application and IPC mechanisms) - Code 100%
- OpenGL (for visualization) - 95% Completed

## How to configure / run the program

- Compile the Code
```bash
make
```
- Run the Program
 ```bash
 ./workers a b c
 ```
  - Then, Open two terminals
    - In First terminal:
    ```bash
    ./plane
    ```
    - In Second terminal:
    ```bash
    ./main
    ```

## Contributers

- Manar Shawahni
- Zainab Jaradat
- Roa Nafi
