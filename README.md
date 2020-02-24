```
fastboot.exe flash uboot u-boot-iTOP-6818.bin
fastboot.exe flash boot boot.img
fastboot.exe flash system system.img
fastboot reboot

setenv bootsystem qt
setenv lcdtype 4.3
saveenv
reset
```
