# STM32L051-dev-board
### ***A small-footprint, custom development PCB for the STM32L051C8Tx***

* This board's MCU is an Access line ultra low power STM32L051C8T6 with 64 kB of flash, 8 kB of SRAM and an ARM Cortex-M0+ core in a 48-pin LQFP package.

* The board supports I<sup>2</sup>C, SPI and UART as communication interfaces. Checkout the datasheet for details.
* Flashing and In-Circuit-Debugging can be achieved through an ST-LINK V3 Mini external flasher / debugger using the SWD protocol. The development board provides an 14 pin connector with 1.27mm pitch (J1) for direct connection to the ST-Link V3 Mini via STDC14 flat
cable. USART2 is available on connector J1 as well. Alternatively, any other suitable programmer can be connected via P1 and jumper wires.
* The board is powered via VPP (+5V) and draws very little current. Power conversion occurs through an onboard 5~3.3V linear regulator.
* The board has a 32.768 kHz clock for RTC capabilities as well as an 8.000 MHz system clock. It also features an indicator LED together with an open drain stage to drive higher current load (both assigned at PC13), a reset button and a boot select jumper.
* The footprint of the board is 32x54 mm and its 2.54 mm pitch headers allow it to be used with standard breadboards.


**I/O connectors Pinout**

| J2     |          |   | J4     |           |
|--------|----------|---|--------|-----------|
| Pin no | Pin name |   | Pin no | Pin name  |
| 1      | GND      |   | 1      | PB9       |
| 2      | Load 1)  |   | 2      | PB8       |
| 3      | PA0      |   | 3      | PB7       |
| 4      | PA1      |   | 4      | PB6       |
| 5      | PA4      |   | 5      | PB5       |
| 6      | PA5      |   | 6      | PB4       |
| 7      | PA6      |   | 7      | PB3       |
| 8      | PA7      |   | 8      | PA15      |
| 9      | PB0      |   | 9      | PA12      |
| 10     | PB1      |   | 10     | PA11      |
| 11     | PB2      |   | 11     | PA10      |
| 12     | PB10     |   | 12     | PA9       |
| 13     | PB11     |   | 13     | PA8       |
| 14     | PB12     |   | 14     | PB15      |
| 15     | PB13     |   | 15     | GND       |
| 16     | PB14     |   | 16     | VPP (+5V) |

*Notes:*

1): assigned to PC13 
