# feserial
A Linux uart driver for the Beaglebone Black.

This driver is based on the lab from Free Electrons:

http://free-electrons.com/doc/training/linux-kernel/

## Building
To build, do the following:
```
cp config .config
export ARCH=arm
export CROSS_COMPILE=arm-linux-gnueabihf-
make
make dtbs
```
