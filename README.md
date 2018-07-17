# Raspberry Pi Pinout
![CoverPhoto](RP2_Pinout.PNG)

# Build u-boot
## Dowload and build uboot images
```
$ git clone git://git.denx.de/u-boot.git
$ make rpi_3_32_defconfig
$ make all
```
## Copy u-boot.bin to RaspberryPi3
```
$ cp u-boot.bin kernel7.img
$ Copy file kernel7.img to SD card (boot/kernel7.img)
```
## Console
![CoverPhoto](https://blog.christophersmart.com/wp-content/uploads/2016/10/rpi-uboot.png)

