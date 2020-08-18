
Debian
====================
This directory contains files used to package nadird/nadir-qt
for Debian-based Linux systems. If you compile nadird/nadir-qt yourself, there are some useful files here.

## nadir: URI support ##


nadir-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nadir-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nadir-qt binary to `/usr/bin`
and the `../../share/pixmaps/nadir128.png` to `/usr/share/pixmaps`

nadir-qt.protocol (KDE)

