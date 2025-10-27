# Computer Vision work


Lab: Dr. Alexander Perez-Pons


## Hardware

![WIOterminal](https://github.com/IGS1I/CpVision/blob/main/assets/wioterminal.jpg)
- [WIO Terminal](https://www.seeedstudio.com/Wio-Terminal-p-4509.html?srsltid=AfmBOoqlsYPOXHmt8u4R_lsj4-dBKGeljw8-h1VOl-1gI1Tt1RUw03Ns)

![ArduCAM](https://github.com/IGS1I/CpVision/blob/main/assets/ArduCAM.jpg)
- [ArduCAM Mini 2MP Plus](https://www.arducam.com/arducam-2mp-spi-camera-b0067-arduino.html)
    - useful guide for testing camera (though no display on WIO terminal): [Iot for Beginners](https://github.com/microsoft/IoT-For-Beginners/blob/main/4-manufacturing/lessons/2-check-fruit-from-device/wio-terminal-camera.md)


### Connections:

| ArduCAM pin | Wio Terminal pin | Description |
|:-----------:|:---------------: |:----------: |
|CS	| 24 (SPI_CS)| SPI Chip Select |
|MOSI| 19 (SPI_MOSI) | SPI Controller Output, Peripheral Input
|MISO| 21 (SPI_MISO) | SPI Controller Input, peripheral Output
|SCK | 23 (SPI_SCLK) | SPI Serial Clock
|GND | 6 (GND) | Ground - 0V
|VCC | 4 (5V) | 5V power supply
|SDA | 3 (I2C1_SDA) | I2C Serial Data
|SCL | 5 (I2C1_SCL)	| I2C Serial Clock
![WioT-Pinout](https://github.com/user-attachments/assets/94fc2df9-f9b1-472f-a142-94c75ece8baa)

## Software

### Necessary Libraries
[ArduCAM](https://github.com/ArduCAM/Arduino/tree/master/ArduCAM) - holds needed functions for arduino cam module