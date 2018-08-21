
Debian
====================
This directory contains files used to package cmpcod/cmpco-qt
for Debian-based Linux systems. If you compile cmpcod/cmpco-qt yourself, there are some useful files here.

## cmpco: URI support ##


cmpco-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cmpco-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cmpcoqt binary to `/usr/bin`
and the `../../share/pixmaps/cmpco128.png` to `/usr/share/pixmaps`

cmpco-qt.protocol (KDE)

