# BusyCircle

## An experiment to compile a program with visual effects for three targets

1.) Windows 2.) Linux 3.) Commodore

Linux and Windows implementations use the SDL2 library from https://www.libsdl.org/ whereas the commodore implementation uses sprites instead which are very well suited for this demonstration. However i wanted to use as much shared code as possible which limited the usage of asm in the commodore target. The commodore routines could be 100x faster when using asm, however as all targets now display what they should i consider this task accomplished. Here are some screen captures from the different targets:

![windows executable](https://github.com/An-S/Busycircle/blob/master/images/windows.PNG)
![c64 executable](https://github.com/An-S/Busycircle/blob/master/images/cbm(c64).PNG)
![linux executable](https://github.com/An-S/Busycircle/blob/master/images/linux.PNG)



    master 


