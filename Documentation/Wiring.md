Wiring
===
HUB75 pins to Stm32
---
The HUB75 pin out, on the LED matrices.

| 1 || 2 | 3 | 4 |
| --- || --- | --- | --- |
| PD0 || R1 | G1 | PD1 |
| PD2 || B1 | GND | GND |
| PD3 || R2 | G2 | PD4 |
| PD5 || B2 | GND | GND |
| PE2 || A | B | PE3 |
| PE4 || C | D | NC |
| PD6 || CLK | STB | PE6 |
| PC6 || OE | GND | GND |

The LED panel on the top-right is where the signal should be piped in from the STM32F4Discovery board, and should be piped in a snake-like fashion to the rest of the panels (left on the top row, right on the bottom row (these panels should be inversed), and left again on the bottom row).

STM32F4Discovery matrix pins
---
| STM32 | Name |
| --- | --- |
| GND | GND (Don't forget to connect this!) |
| PD0 | R1 |
| PD1 | G1 |
| PD2 | B1 |
| PD3 | R2 |
| PD4 | G2 |
| PD5 | B2 |
| PE2 | A |
| PE3 | B |
| PE4 | C |
| PE5 | D (may be left unconnected for 1/8th scan) |
| PD6 | CLK |
| PE6 | STB |
| PC6 | OE |
