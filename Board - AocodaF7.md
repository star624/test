# AocodaF7

### Features

- STM32F722

- 16 MB of Flash

- USB VCP and boot button for DFU  

- Dual Gyro via SPI (MPU6000 + ICM20602)

- I2C device extend(Baro/compass/Oled etc)

- VTX Power Switch

- 9V BEC for VTX and Camera

- Curr RSSI sensors input

- OSD integration AT7456

- integration Bluetooth module (active, when board isnt armed)

- WS2812 LED Output

- IRC Tramp

- 3S-6S Input

### Connections

| Function      | SolderPad/SilkScreen | Rescource | MCU Pin      | Notes                                  |
|:-------------:|:--------------------:|:---------:|:------------:|:--------------------------------------:|
| SBUS          | SBUS                 | RX1       | PA10         | No Inverter                            |
| UART1         | TX1                  | TX1       | PA9          |                                        |
| ESC Telemetry | TEL                  | RX4       | PA1          | Halfduplex by default                  |
| UART4         | TX4                  | TX4       | PA0          |                                        |
| Cam Control   | CC                   |           | PB6          |                                        |
| Video Output  | VTX                  | -         | -            |                                        |
| Cameram input | CAM                  | -         | -            |                                        |
| WS2812        | LED                  | LED_STRIP | PB7          |                                        |
| BUZZER        | BZ-                  | BEEPER    | PC13         |                                        |
| S1-S4         | M1-M4                |           | C9/C8/C7/C6  | Motor Outputs                          |
| S5-S6         |                      |           | PB1/PA8      | Motor Outputs                          |
| UART2         | TX2/RX2              | TX2/RX2   | PA2/PA3      |                                        |
| UART3         | TX3/RX3              | TX3/RX3   | PC10/PC11    |                                        |
| UART5         | Bluethoth            | TX5/RX5   | PC12/PD2     |                                        |
| VBAT          | BAT                  | -         | -            | 3S-6S input                            |
| Current       | CURR                 | -         | PC1          | on bottom                              |
| SDA           | SDA                  | I2C1_SDA  | PB9          |                                        |
| SCL           | SCL                  | I2C1_SCL  | PB8          |                                        |


### Connections


### Designer
* mark&AOCODA-RC
