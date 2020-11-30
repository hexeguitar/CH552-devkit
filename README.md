# CH552 devkit

### CH552 development board with hardware reboot into bootloader feature.  

<img src="pics/ch552_devkit1.jpg " width="600">  
 
<img src="pics/ch552_devkit2.jpg " width="600">  

### Reboot circuit  

<img src="pics/reboot_schm.png " width="600">  

Pressing and releasing the BOOTLOADER button will cycle the power and start the MCU with 1k pull-up on the USB-P line. This will start the built in USB/Serial bootoader. External BOOT input is provided for triggering via DTR or other active low signal.  

Take a look here for similar circuit for the CH559 series:  
https://github.com/hexeguitar/CH55x-HW-reboot  

Python programming script for both USB and serial port can be found here:  
https://github.com/hexeguitar/CH55x_python_flasher  
___
(c) 11.2020 by Piotr Zapart  
www.hexefx.com

[pic1]: pics/ch552_devkit1.jpg "CH552 devkit"
[pic2]: pics/ch552_devkit2.jpg "CH552 devkit"
