
Debian
====================
This directory contains files used to package brixcoind/brixcoin-qt
for Debian-based Linux systems. If you compile brixcoind/brixcoin-qt yourself, there are some useful files here.

## brixcoin: URI support ##


brixcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install brixcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your brixcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/brixcoin128.png` to `/usr/share/pixmaps`

brixcoin-qt.protocol (KDE)

