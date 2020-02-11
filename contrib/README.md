
Debian
====================
This directory contains files used to package ledurod/leduro-qt
for Debian-based Linux systems. If you compile ledurod/leduro-qt yourself, there are some useful files here.

## leduro: URI support ##


leduro-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install leduro-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your leduroqt binary to `/usr/bin`
and the `../../share/pixmaps/leduro128.png` to `/usr/share/pixmaps`

leduro-qt.protocol (KDE)

