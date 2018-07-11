
Debian
====================
This directory contains files used to package QUARd/QUAR-qt
for Debian-based Linux systems. If you compile QUARd/QUAR-qt yourself, there are some useful files here.

## QUAR: URI support ##


QUAR-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install QUAR-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your QUAR-qt binary to `/usr/bin`
and the `../../share/pixmaps/QUAR128.png` to `/usr/share/pixmaps`

QUAR-qt.protocol (KDE)

