<div align="center">

# SUDOKU

</div>
   
# Introduction

# General Description

# Hardware Design
#### Component List : 
| Name                               | Source                   |
|------------------------------------|--------------------------|
| Arduino Uno                        | University Of Bucharest  |
| LCD display 1.8" with SPI and controller TFT ST7735                  | Optimusdigital      |                  
| Connecting Wires                   | University Of Bucharest  | 
| Breadboard                         | University Of Bucharest  |
| Keypad 4*4 with mother pins        | Optimusdigital           |

## Pins Configuration

### TFT Display Pinout and Connections:

| **Component**            | **Arduino Pin** | **Function Description**                                                      |
|--------------------------|-----------------|-------------------------------------------------------------------------------|
| **SCK (Clock)**           | Pin 13          | Clock signal for communication with the display (SCK for SPI)                 |
| **SDA (Data Input)**      | Pin 11          | Data input for the display (MOSI for SPI)                                    |
| **RES (Reset)**           | Pin 10          | Resets the display                                                           |
| **DC (Data/Command)**     | Pin 12          | Controls whether data or command is being sent (Data/Command)                |
| **CS (Chip Select)**      | Pin A0          | Activates the display for communication (Chip Select)                         |
| **BL (Backlight)**        | 3.3V (or GND with a resistor for PWM control) | Controls backlight brightness (via resistor or PWM control for brightness) |
| **VCC (Power)**           | 3.3V            | Power supply for the display (must be 3.3V to avoid damage)                   |
| **GND (Ground)**          | GND             | Ground connection                                                            |

### Keypad Pinout and Connections:

| **Component**            | **Arduino Pin** | **Function Description**                                                      |
|--------------------------|-----------------|-------------------------------------------------------------------------------|
| **Row 1**                | Pin 2           | Row 1 of the keypad                                                          |
| **Row 2**                | Pin 3           | Row 2 of the keypad                                                          |
| **Row 3**                | Pin 4           | Row 3 of the keypad                                                          |
| **Row 4**                | Pin 5           | Row 4 of the keypad                                                          |
| **Column 1**             | Pin 6           | Column 1 of the keypad                                                       |
| **Column 2**             | Pin 7           | Column 2 of the keypad                                                       |
| **Column 3**             | Pin 8           | Column 3 of the keypad                                                       |
| **Column 4**             | Pin 9           | Column 4 of the keypad                                                       |


# Software Design
For this project, I am using PlatformIO as the development environment.
# Results
# Conclusions
