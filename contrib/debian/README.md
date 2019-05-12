
Debian
====================
This directory contains files used to package cbslcoind/cbslcoin-qt
for Debian-based Linux systems. If you compile cbslcoind/cbslcoin-qt yourself, there are some useful files here.

## cbslcoin: URI support ##


cbslcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cbslcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cbslcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/cbslcoin128.png` to `/usr/share/pixmaps`

cbslcoin-qt.protocol (KDE)

