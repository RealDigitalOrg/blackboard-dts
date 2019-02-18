# Device tree source files for Blackboard

This repository includes the source files for the device tree used when booting the Linux kernel on Blackboard.  These files are located in "/root/Src/dts" on the default SD card image for Blackboard.

There is a script file in /root/Scripts that will recompile the device tree.  The resulting file, "devicetree.dtb", can be copied to /boot after mounting it with the command:

```
sudo mount /dev/mmcblk0p1 /boot
```
