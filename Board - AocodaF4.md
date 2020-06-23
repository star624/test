# AocodaF4

### Features

- STM32F405

- 16MB of SPI Flash

- USB VCP and boot button for DFU

- MPU6000

- I2C device extend(Baro/compass/Oled etc)

- Curr RSSI sensors input

- 9V BEC for VTX and Camera

- Camera Control

- OSD integration AT7456

- WS2812 LED Output

- IRC Tramp

- 3S-6S Input

### Connections

| Function      | SolderPad/SilkScreen | Rescource | MCU Pin      | Notes                                  |
|:-------------:|:--------------------:|:---------:|:------------:|:--------------------------------------:|
| SBUS          | SBUS                 | RX1       | PA10         | No Inverter                            |
| UART1         | TX1                  | TX1       | PA9          |                                        |
| ESC Telemetry | TEL                  | RX5       | PD2          |                                        |
| uART5         | TX5                  | TX5       | PC12         |                                        |
| Cam Control   | CC                   | PB8       | PB8          |                                        |
| Video Output  | VTX                  | -         | -            |                                        |
| Cam Input     | CAM                  | -         | -            |                                        |
| WS2812        | LED                  | LED_STRIP | PB1          |                                        |
| BUZZER        | BZ-/                 | BEEPER    | PB0          |                                        |
| S1-S2         | M1-M2                |           | PC9/PC8      | Motor Outputs                          |
| S3-S4         | M3-M4                |           | PC7/PC6      | Motor Outputs                          |
| S5-S6         |                      |           | PA15/PA8     | Motor Outputs                          |
| UART2         | TX2/RX2              | TX2/RX2   | PA2/PA3      |                                        |
| UART3         | TX3/RX3              | TX3/RX3   | PC10/PC11    |                                        |
| UART4         | TX4/RX4              | TX4/RX4   | PA0/PA1      |                                        |
| VBAT          | BAT                  | -         | -            | 3S-6S input                            |
| Current       | CURR                 | -         | PC1          |                                        |
| RSSI          | RSSI                 | -         | PC3          |                                        |
| SDA           | SDA                  | I2C1_SDA  | PB7          |                                        |
| SCL           | SCL                  | I2C1_SCL  | PB6          |                                        |

### Gyro & ACC ,suppose MPU6000
| Value | Identifier   | function |  pin   | Notes                                                                                 |
| ----- | ------------ | ---------| -------| ------------------------------------------------------------------------------------- |                                                                                      
| 1     | SPI1         |    SCK   |  PA5   | 
| 2     | SPI1         |    MISO  |  PA6   | 
| 3     | SPI1         |    MOSI  |  PA7   | 
| 4     | SPI1         |    CS    |  PB11  | 

### OSD AT7456
| Value | Identifier   | function |  pin   | Notes                                                                                 |
| ----- | ------------ | ---------| -------| ------------------------------------------------------------------------------------- |                                                                                      
| 1     | SPI2         |    SCK   |  PB13  | 
| 2     | SPI2         |    MISO  |  PB14  | 
| 3     | SPI2         |    MOSI  |  PB15   | 
| 4     | SPI2         |    CS    |  PB10  |

### 16Mbyte flash
| Value | Identifier   | function |  pin   | Notes                                                                                 |
| ----- | ------------ | ---------| -------| ------------------------------------------------------------------------------------- |                                                                                      
| 1     | SPI3         |    SCK   |  PB3  | 
| 2     | SPI3         |    MISO  |  PB4  | 
| 3     | SPI3         |    MOSI  |  PB5   | 
| 4     | SPI3         |    CS    |  PC0  |

### Designer
* mark&AOCODA-RC




