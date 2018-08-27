
Debian
====================
This directory contains files used to package thotd/thot-qt
for Debian-based Linux systems. If you compile thotd/thot-qt yourself, there are some useful files here.

## thot: URI support ##


thot-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install thot-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your thotqt binary to `/usr/bin`
and the `../../share/pixmaps/thot128.png` to `/usr/share/pixmaps`

thot-qt.protocol (KDE)

