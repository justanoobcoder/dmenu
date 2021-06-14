# dmenu - dynamic menu

## About
dmenu is a dynamic menu for X, originally designed for dwm. It manages large numbers of user-defined menu items efficiently.

## Patches
This is my custom dmenu build. It contains these patches:
+ [alpha](https://tools.suckless.org/dmenu/patches/alpha/)
+ [border](https://tools.suckless.org/dmenu/patches/border/)
+ [case-insensitive](https://tools.suckless.org/dmenu/patches/case-insensitive/)
+ [center](https://tools.suckless.org/dmenu/patches/center/)
+ [emoji-highlight](https://tools.suckless.org/dmenu/patches/emoji-highlight/)
+ [fuzzyhighlight](https://tools.suckless.org/dmenu/patches/fuzzyhighlight/)
+ [fuzzymatch](https://tools.suckless.org/dmenu/patches/fuzzymatch/)
+ [line-height](https://tools.suckless.org/dmenu/patches/line-height/)
+ [mouse-support](https://tools.suckless.org/dmenu/patches/mouse-support/)
+ [password](https://tools.suckless.org/dmenu/patches/password/)

## Installation
Edit config.mk file to match your local setup (st is installed into
the `/usr/local` namespace by default).

Afterwards enter the following command to build and install st:
```
sudo make install clean
```

## Uninstallation
To uninstall dmenu, go to source code folder and run the following command:
```
sudo make uninstall
```

## Configuration
The configuration of st is done by editing the config.def.h file and (re)compiling the source code.
```
sudo make install clean
```
