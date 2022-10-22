# st-geir 0.8.4

Patches included:

* alphaFocusHighlight
* scrollback
* scrollback-mouse
* scrollback-mouse-altscreen

This version of st uses the following two fonts:

* hack nerd font
* hack

Hack font is usually found in your distro's repo. For Debian-based systems:

	$ sudo apt install fonts-hack

For Arch-based systems:

	$ sudo pacman -S ttf-hack ttf-hack-nerd

Hack Nerd Font can be downloaded from https://www.nerdfonts.com/font-downloads

## Installation

Clone this repo and compile from source:

	$ git clone https://github.com/geirda/st-geir.git
	$ cd st-geir
	$ sudo make clean install

## OpenBSD:

	$ git clone https://github.com/geirda/st-geir.git
	$ cd st-geir
	$ git checkout openbsd
	$ doas make clean install

## For Arch users:

Download the file PKGBUILD, create and install the package:

	$ wget https://raw.githubusercontent.com/geirda/st-geir/main/PKGBUILD
	$ makepkg -ci

Precompiled packages for Arch: https://github.com/geirda/Arch/tree/master/suckless/st/


![suckless](https://raw.githubusercontent.com/geirda/Arch/master/suckless/suckless.png)
