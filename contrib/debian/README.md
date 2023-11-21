
Debian
====================
This directory contains files used to package mastercored/mastercore-qt
for Debian-based Linux systems. If you compile mastercored/mastercore-qt yourself, there are some useful files here.

## pivx: URI support ##


mastercore-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mastercore-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mastercore-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

mastercore-qt.protocol (KDE)

