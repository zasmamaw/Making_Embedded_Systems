Exercise 3a
******
Investigate project board

Look at the documents for the board you are considering for your final project (or any ST Discovery Board), draw the hardware block diagram for the board. For peripherals, note the communication paths (SPI, I2C, etc).

Look at the datasheet for the processor and other documents. Answer these questions:

-What kind of processor is it?

-How much Flash and RAM does it have? Any other memory types?

-Does it have any special peripherals? (List 3-5 that you noted as being interesting.)

-Does it have a floating point unit?

-If it has an ADC, what are the features?

Look at one application note for this processor.

********

The board I am considering for my project is the STM32U5 DISCOVERY KIT FOR IOT (B-U585I-IOT02A).  I chose this board primarily for the rich set of sensors that it includes.  Below is the hardware block diagram, along with wide variety of peripheral devices that it features:

<img width="639" alt="Screen Shot 2021-12-02 at 6 34 32 PM" src="https://user-images.githubusercontent.com/34926684/144535099-c7efa98d-b56a-4f36-b30c-d48c728c4ee0.png">

-The processor is the STM32U585AI, which is based on the Arm Cortex-M33 core.

-The processor has 2 Mbytes of Flash memory and 786 Kbytes of SRAM.  It has external memory interface supporting SRAM, PSRAM, NOR, NAND and FRAM memories, as well as 2 Octo-SPI memory interfaces.

-It includes various "peripheral blocks".  It has 24 capacitive sensing channels (to support touch key, linear and rotary touch sensors), 22 communication peripherals (such as USB,  SAI, I2C, USART, SPI, etc),  various circuits and coprocessors dedicated to security and cryptography.

-It has Floating-point arithmetic functionality with support for single precision arithmetic.

-It has 14-bit ADC 2.5-Msps as well as 12-bit ADC 2.5-Msps.

-I reviewed the "Getting started with STM32CubeU5 for STM32U5 Series".  It was quite detailed, but it was relevant to me since I wanted to get started exploring the SW eco system and this had both breadth and depth.



