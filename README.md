# Embedded Systems project
## An autonomous Line Tracking & Controlled Car using Mobile Application by stm32 Microcontroller based on ARM Cortex M3

### Description
*   Car has two modes which are selected by user through Mobile Application
*  First mode  : Controlled Car through mobile application to move either forward or backward or right or left
*  Second mode : Autonomous Car which follow a Line Track


### Hardware 
* STM32 Mircocontroller [ ARM Cortex M3 ]
* Motor driver L298
* 4 DC Motors
* 2 IR Sensors
* Bluetooth module HC-05
* 3 Lithium batteries
* Breadboard

### Software Layered Architecture
#### App --> Application
* main
#### HAL --> Hardware abstraction layer
* Motor
* IR Sensor
#### MCAL   --> Mircocontroller abstraction layer
* RCC       --> Reset & clock control to configure System & Peripherals Clock
* GPIO      --> General Purpose Input Output
* USART1    --> Universal Synchronous Asynchronous Receiver Transmitter
* TIMER 4   --> Timer Peripheral to generate PWM signal

### Driver files
* program.c     --> contains application public interfaces [ API ]
* interface.h   --> contains function declaration & Macros
* config.h      --> contains Configurations 
* private.h     --> contains registers defination
 
## Contributing  
### We welcome contributions from the community. To contribute to [Autonomous Controlled Car], please follow these steps:
* Fork the repository.
* Create a new branch for your feature or bug
