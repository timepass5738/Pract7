Pins on RFID RC522      Pins on Raspberry pi      Function
SDA                         24                 GPIO8 (SPI_CE0_N)
SCK                          23                GPIO11 (SPI0-_CLK)
MOSI                          19                GPIO10 (SPI0_MOSI)
MISO                          21                GPIO9 (SPI0_MISO)
IRQ                        NOT IN  USE
GND                          6                    Ground
RST                          22
3.3V                           1

Update: sudo apt-get update
Upgrade: sudo apt-get upgrade
Enable I2C: sudo raspi-config
Check SPI: lsmod | grep spi
Python: sudo apt-get install python3-dev python3-pip
Spidev: sudo apt-get install  spidev
MFRC522: git clone  https://github.com/pimylifeup/MFRC522-python
