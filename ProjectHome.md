# VMXOS #
The project is made to have a native vmx support based on a simple operating system. This is just a series of experiments to learn more on hardware virtualizzation support, with a focus on Intel vmx.

For more informations about the project

![http://www.omam.it/my.png](http://www.omam.it/my.png)

## Latest version Notes ##
Bios Parameter Block is not actually supported, so in order to make the system bootable from my Sandik Cruizer pen drive I've been hard coded the Hidden Sectors offset to 0x2C in boot.asm, but this is only when the image is booted from an hard drive (POST passes dl=0x80), so from floppy should work properly.

## Latest Screenshot ##
![http://vmxos.googlecode.com/svn/screenshots/vmxos_latest.jpg](http://vmxos.googlecode.com/svn/screenshots/vmxos_latest.jpg)