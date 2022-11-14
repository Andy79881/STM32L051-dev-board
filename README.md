# STM32L051-dev-board
### ***A small-footprint, custom development PCB for the STM32L051C8Tx***

* This board's MCU is an Access line ultra low power STM32L051C8T6 with 64 kB of flash, 8 kB of SRAM and an ARM Cortex-M0+ core in a 48-pin LQFP package.

* The board supports I<sup>2</sup>C, SPI and UART as communication interfaces. Checkout the datasheet for details.
* Flashing and In-Circuit-Debugging can be achieved through an ST-LINK V3 Mini external flasher / debugger using the SWD protocol. The development board provides an 14 pin connector with 1.27mm pitch (J1) for direct connection to the ST-Link V3 Mini via STDC14 flat
cable. USART2 is available on connector J1 as well. Alternatively, any other suitable programmer can be connected via P1 and jumper wires.
* The board is powered via VPP (+5V) and draws very little current. Power conversion occurs through an onboard 5~3.3V linear regulator.
* The board has a 32.768 kHz clock for RTC capabilities as well as an 8.000 MHz system clock. It also features an indicator LED together with an open collector stage to drive higher current load (both assigned at PC13), a reset button and a boot select jumper.
* The footprint of the board is 32x54 mm and its 2.54 mm pitch headers allow it to be used with standard breadboards.

---

**I/O connectors (J2, J4) Pinout 1)**

<table>
<tr>
<th>J2</th>
<th>J4</th>
</tr>
<tr>

<td>

| Pin no | Pin name  |
|--------|-----------|
| 1      | GND       |
| 2      | Load 2)   |
| 3      | PA0       |
| 4      | PA1       |
| 5      | PA4       |
| 6      | PA5       |
| 7      | PA6       |
| 8      | PA7       |
| 9      | PB0       |
| 10     | PB1       |
| 11     | PB2       |
| 12     | PB10      |
| 13     | PB11      |
| 14     | PB12      |
| 15     | PB13      |
| 16     | PB14      |

</td><td>

| Pin no | Pin name  |
|--------|-----------|
| 1      | PB9       |
| 2      | PB8       |
| 3      | PB7       |
| 4      | PB6       |
| 5      | PB5       |
| 6      | PB4       |
| 7      | PB3       |
| 8      | PA15      |
| 9      | PA12      |
| 10     | PA11      |
| 11     | PA10      |
| 12     | PA9       |
| 13     | PA8       |
| 14     | PB15      |
| 15     | GND       |
| 16     | VPP (+5V) |

</td></tr> </table>

**Notes:**
1. J2 left, J4 right for PCB front view
2. PC13 assigned to open collector output and built-in LED 


| Front view | Rear view |
|------------|-----------|
|![grafik](https://user-images.githubusercontent.com/57663237/201778979-8aca7a73-d306-4409-b94e-c68bb08bab90.png)            |![grafik](https://user-images.githubusercontent.com/57663237/201779175-c74a656a-946b-4f7a-a700-879fb4db7b7b.png)           |

SWD debug / programming connector for ST-link V3 mini highlighted.

