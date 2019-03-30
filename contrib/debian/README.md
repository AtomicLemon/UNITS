
Debian
====================
This directory contains files used to package unitsd/units-qt
for Debian-based Linux systems. If you compile unitsd/units-qt yourself, there are some useful files here.

## units: URI support ##


units-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install units-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your unitsqt binary to `/usr/bin`
and the `../../share/pixmaps/units128.png` to `/usr/share/pixmaps`

units-qt.protocol (KDE)

