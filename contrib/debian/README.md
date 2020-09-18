
Debian
====================
This directory contains files used to package nasdacashd/nasdacash-qt
for Debian-based Linux systems. If you compile nasdacashd/nasdacash-qt yourself, there are some useful files here.

## nasdacash: URI support ##


nasdacash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nasdacash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nasdacash-qt binary to `/usr/bin`
and the `../../share/pixmaps/nasdacash128.png` to `/usr/share/pixmaps`

nasdacash-qt.protocol (KDE)

