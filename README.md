# dmenu - dynamic menu

## About
dmenu is a dynamic menu for X, originally designed for dwm. It manages large numbers of user-defined menu items efficiently. This is a patched dmenu with Nord theme.

## Screenshots
![Pic1](./img/screenshot1.png)
![Pic2](./img/screenshot2.png)
![Pic3](./img/screenshot3.png)

## Patches
This is my custom dmenu build. It contains these patches:
+ <a href="https://tools.suckless.org/dmenu/patches/alpha/" target="_blank">alpha</a>
+ <a href="https://tools.suckless.org/dmenu/patches/border/" target="_blank">border</a>
+ <a href="https://tools.suckless.org/dmenu/patches/case-insensitive/" target="_blank">case-insensitive</a>
+ <a href="https://tools.suckless.org/dmenu/patches/center/" target="_blank">center</a>
+ <a href="https://tools.suckless.org/dmenu/patches/emoji-highlight/" target="_blank">emoji-highlight</a>
+ <a href="https://tools.suckless.org/dmenu/patches/fuzzyhighlight/" target="_blank">fuzzyhighlight</a>
+ <a href="https://tools.suckless.org/dmenu/patches/fuzzymatch/" target="_blank">fuzzymatch</a>
+ <a href="https://tools.suckless.org/dmenu/patches/line-height/" target="_blank">line-height</a>
+ <a href="https://tools.suckless.org/dmenu/patches/mouse-support/" target="_blank">mouse-support</a>
+ <a href="https://tools.suckless.org/dmenu/patches/password/" target="_blank">password</a>

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
