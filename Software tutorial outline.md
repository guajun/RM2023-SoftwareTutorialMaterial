# Software tutorial outline
> *Chronological order*
### General sense for R&D
1. Google
2. StackOverflow
3. Copy
4. Experiment
    Try to understand the blackbox with some certain inputs to get the rules

## Git
+ [中文Git教程](https://www.runoob.com/git/git-tutorial.html)
+ Markdown documentation


## C/C++ basics
+ Read more from the ready-made online documents
    [English C Tutorials](https://www.w3schools.com/c/index.php)
    [English C++ Tutorials](https://www.w3schools.com/cpp/default.asp)

    [中文C教程](https://www.runoob.com/cprogramming/c-tutorial.html)
    [中文C++教程](https://www.runoob.com/cplusplus/cpp-tutorial.html)


+ No std library
+ Projects using key concepts and simulating real RM R&D situation
    1. DR16 data decoding(provide actual DR16 messages)
    2. Modularization programming
+ *Maybe test in later projects, not current ones*

## Bridging from desktop to embedded system

### Debug
+ Debugger
+ Communication between MCU and PC

### Interrupt
+ Asynchronous programming

### Peripherals
+ Instructions and data transfer by reading from and writing to registers of the peripherals


## STM32

### 1. STM32CubeMX & HAL

### 2. Electronics basics
+ Pull-up resistors
+ Pull-down resistors
+ Meters(Volt, Ohm, Connectivity)
+ Signal interference and noise

### 3. GPIO
+ Blinking onboard LED
+ Responsing to onboard button

### 4. Timer & PWM
+ Ultrasonic sensor
+ Servo
+ Hall sensor encoder
+ [Getting Started with STM32 - Timers and Timer Interrupts](https://www.digikey.hk/en/maker/projects/getting-started-with-stm32-timers-and-timer-interrupts/d08e6493cefa486fb1e79c43c0b08cc6)


### 5. PWM with DMA
+ Control WS2812 led strips
+ Try to bring them with sense of using datasheet

### 6. UART communication
+ DR16 receiving

### 7. CAN communication
+ Read from ESC feedback

## Control theory

### PID
+ Sine wave RPM

## FreeRTOS
[Introduction to RTOS - Digi-Key Electronics](https://youtube.com/playlist?list=PLEBQazB0HUyQ4hAPU1cJED6t3DU0h34bz)


## Final project

### Little car

### Huge car
