# Keyboard and trackpad

Found somewhere that you could use these connections. You can also use the ribbon cable, but I havent investigated what the pinouts are.
The bottom fpc connector is for trackpad click only.

In windows the keyboard/trackpad worked fine out of the box.
For Raspbian the trackpad was not working from start, I found out the driver is no longer built/included by default in most linux kernels.
I compiled the appletouch driver module and insmodded it and it worked, you can find it in kernel sources and either recompile the entire kernel or compile as a module.

Appletouch [driver](https://github.com/raspberrypi/linux/tree/rpi-5.10.y/drivers/input/mouse)



   ![USB connection](https://i.imgur.com/i5GxgSH.jpeg)

Blogger showing pinouts [bounav](https://bounav.wordpress.com/2009/02/28/macbook-pro-trackpad-conversion)


![ ](https://i.imgur.com/e6CBXZv.jpg)

Glued power indicator from powerbank on the keyboard
