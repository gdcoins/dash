
Debian
====================
This directory contains files used to package gdcoind/gdcoin-qt
for Debian-based Linux systems. If you compile gdcoind/gdcoin-qt yourself, there are some useful files here.

## gdcoin: URI support ##


gdcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gdcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gdcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/gdcoin128.png` to `/usr/share/pixmaps`

gdcoin-qt.protocol (KDE)

