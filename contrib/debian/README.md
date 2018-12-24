
Debian
====================
This directory contains files used to package dodd/dod-qt
for Debian-based Linux systems. If you compile dodd/dod-qt yourself, there are some useful files here.

## dod: URI support ##


dod-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dod-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dodqt binary to `/usr/bin`
and the `../../share/pixmaps/dod128.png` to `/usr/share/pixmaps`

dod-qt.protocol (KDE)

