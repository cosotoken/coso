
Debian
====================
This directory contains files used to package cosod/coso-qt
for Debian-based Linux systems. If you compile cosod/coso-qt yourself, there are some useful files here.

## coso: URI support ##


coso-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install coso-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cosoqt binary to `/usr/bin`
and the `../../share/pixmaps/coso128.png` to `/usr/share/pixmaps`

coso-qt.protocol (KDE)

