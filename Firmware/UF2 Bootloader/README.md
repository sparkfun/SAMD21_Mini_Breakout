UF2 Bootloader for the SAMD21 Mini Breakout
==========================================
**Current Version**: UF2 Bootloader v3.2.2-1-gdec2fb7-dirty SFHWRO
**Updated**: 2/20/2019

What is UF2? It's probably best to read the documents [HERE](https://makecode.com/blog/one-chip-to-flash-them-all). The TLDR however, is that it's a bootloader that turns your micro-controller 
into a flash drive. The example bootloader provided here was created 2/20/2019
and further support is not guaranteed. However you can learn a bit about _how_
to build your own bootloader at Microsoft's [repo](https://github.com/Microsoft/uf2).
The hardest part will be ensuring that you have all the necessary build dependencies.

To update your SAMD21 Mini with the bootloader is simple. If you already have a
bootloader on it, i.e. you can see it populate in Arduino and/or Device
Manager, then all you have to do is open the "Update-Bootloader.ino" sketch and
upload it. Afterwards, you should see the SAMD21 pop up as a **SPARKFUN** drive. 
I have also included an "update" binary file for those that want to use some
GUI or command line interface instead, as well as _just_ the bootloader for
those that don't already have a bootloader installed on their micro-controller.

Circuit Python 
------------------
**Current Version**: Adafruit CircuitPython 4.0.0-beta.1-46-g3d0757102  
**Updated**: 2/20/2019

Circuit Python is Adafruit's version of Micro Python. You can read general
information about it [HERE](https://learn.adafruit.com/welcome-to-circuitpython).
They also have some documentation on how to build a version of Circuit Python
on their website [here](https://learn.adafruit.com/building-circuitpython/build-circuitpython). 
I have included a build of it under the Circuit Python folder. Assuming that
you have uploaded the UF2 bootloader above, than all you need to do is drag and
drop the UF2 file in the Circuit Python folder into your **SPARKFUN** drive and 
you're good to go! The Sparkfun drive will momentarily disappear and a **CIRCUITPY** 
drive will take its place. 


