
Debian
====================
This directory contains files used to package globalsmartassetd/globalsmartasset-qt
for Debian-based Linux systems. If you compile globalsmartassetd/globalsmartasset-qt yourself, there are some useful files here.

## globalsmartasset: URI support ##


globalsmartasset-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install globalsmartasset-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your globalsmartassetqt binary to `/usr/bin`
and the `../../share/pixmaps/globalsmartasset128.png` to `/usr/share/pixmaps`

globalsmartasset-qt.protocol (KDE)

