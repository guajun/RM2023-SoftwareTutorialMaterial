# Software tutorial outline

## Tutorial target 
+ Preparation of **internal competition**
+ Bring methodology of engineers
+ Become familiar with the frame of technical software skills required in Robomaster

## General sense for R&D
+ [Google](https://www.google.com/)
+ [StackOverflow](https://stackoverflow.com/)
+ [w3schools](https://www.w3schools.com/)
+ [Runoob (zh-CN)](https://www.runoob.com/)
+ Copy
+ Experiment
    Try to understand the blackbox with some certain inputs to get the rules

## General resources
+ CN
[RoboMaster电控入门 | sasasatori](https://www.cnblogs.com/sasasatori/tag/RoboMaster%E7%94%B5%E6%8E%A7%E5%85%A5%E9%97%A8/)
[]
## Git
+ Environment setup
+ Command Line Interface
+ [中文Git教程](https://www.runoob.com/git/git-tutorial.html)
+ [Git Tutorials](https://www.w3schools.com/git/)
+ Markdown documentation

### Task
+ Create a new repository
+ Invite Seniors as collaborator
+ Add the specified content to the README.md with specified format

## C/C++ basics
+ Read from the ready-made online documents(for desktop programming)
    [C Tutorials](https://www.w3schools.com/c/index.php)
    [C++ Tutorials](https://www.w3schools.com/cpp/default.asp)

    [中文C 教程](https://www.runoob.com/cprogramming/c-tutorial.html)
    [中文C++ 教程](https://www.runoob.com/cplusplus/cpp-tutorial.html)


+ No std library
+ Projects using key concepts and simulating real RM R&D situation

### Tasks
1. DR16 data decoding(provide actual DR16 messages)
2. Modularization programming
3. Motor class

+ Written as APIs in serveral modules
+ Maybe only function prototype and data structure
+ Ready to use in later final project and possibly internal competition


## Bridging from desktop to embedded system

### Environments
+ Complier
+ Environment setup for debugger
### Debug
+ Debugger
+ Communication between MCU and PC
+ Reset button to restart program

### Interrupt
+ Asynchronous programming

### Peripherals
+ Instructions and data transfer by reading from and writing to registers of the peripherals.
+ Registers of peripherals are accessed like memory, but with certain address offset.
+ Some peripherals are able to access memory other than registers of themselves, like FDCAN, DMA

## STM32 R&D

### 1. STM32CubeMX & HAL
+ CubeMX Version
##### Select MCU
+ STM32F103C8T6
##### Pinout & Configuration
+ System Core
    + SYS
    + RCC
    + DEBUG
    + GPIO
    + DMA
+ Timer
    + TIMx
+ Connectivity
    + UART
    + CAN
##### Clock Configuration
+ Config frequency multiplication to reach maximum
##### Project Manager
+ Toolchain / IDE - Makefile
+ Code Generator

***CubeMX configs can be done according to progress of tutorials***
#### Tasks
Generate a project and able to compile

### 2. Electronics basics
+ Pull-up resistors
+ Pull-down resistors
+ Meters (Volt, Ohm, Connectivity)
+ Signal interference and noise

### 3. GPIO
+ Blinking onboard LED
+ Responsing to onboard button

### 4. Timer & PWM
#### Structure of the peripheral
+ Clock
+ Counter register
+ Auto reload register
+ Output compare / Input capture register

#### Tasks
+ Ultrasonic sensor
+ Servo
+ Hall sensor encoder

+ [Getting Started with STM32 - Timers and Timer Interrupts](https://www.digikey.hk/en/maker/projects/getting-started-with-stm32-timers-and-timer-interrupts/d08e6493cefa486fb1e79c43c0b08cc6)


### 5. PWM with DMA
#### DMA(Direct Memory Acesss)
+ Reduce cpu loads

#### Task
+ **WS2812**
+ Will provide a WS2812 extension board
+ Control WS2812 led strips
+ Try to bring them with sense of using datasheet
#### Notes
+ DMA concepts are important to 

### 6. UART communication
#### Setup
+ Baud rate
+ Wiring
+ 串口调试助手 / Serial Debug Assistant 
+ USB to TTL
#### Tasks
+ DR16 receiving

### 7. CAN communication

+ [**CAN Bus - Wikipedia**](https://en.wikipedia.org/wiki/CAN_bus)
+ Protocol
    + Differential voltage
    + Frame structure
    + Baud rate
    + Bit Timing
[CAN stuff bit](https://stackoverflow.com/questions/31880366/bit-stuffing-in-can-bus)
+ High refresh rate, thus require handling in the interrupts
+ Read from ESC feedback

## Control theory
### PID
#### Task
+ Sine wave RPM control

## FreeRTOS
### Online resources
+ [[Youtube playlist] Introduction to RTOS - Digi-Key Electronics (Strongly recommend)](https://youtube.com/playlist?list=PLEBQazB0HUyQ4hAPU1cJED6t3DU0h34bz)
+ [FreeRTOS Kernel Developer Docs](https://www.freertos.org/features.html)
+ [API Reference](https://www.freertos.org/a00106.html)

### 
+ Task Scheduling
+ Interrupt
+ Task Control
+ Semaphore / Mutexes
+ Queue


## Final project
+ Target: test all knowlege taught through the tutorial

### Little car

### Huge car
