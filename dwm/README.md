DWM - clean and light purple ricing
===================================

Packages
--------
Needed package for this config: 
	-nerd-fonts
	-noto-fonts-emoji

Patch
-----
In order to run the basic configuration you need these three patches:

	-uselessgap
	-alwayscenter
	-attachbelow


Installation
------------
Edit config.mk to match your local setup

Afterwards enter the following command to build and install dwm (if
necessary as root):

    make clean install


Running dwm
-----------
Add the following line to your .xinitrc to start dwm using startx:

    exec dwm


Configuration
-------------
The configuration of dwm is done by creating a custom config.h
and (re)compiling the source code.

Ricing
--------
This config is my first attempt of ricing dwm
