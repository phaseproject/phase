
Debian
====================
This directory contains files used to package phased/phase-qt
for Debian-based Linux systems. If you compile phased/phase-qt yourself, there are some useful files here.

## phase: URI support ##


phase-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install phase-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your phase-qt binary to `/usr/bin`
and the `../../share/pixmaps/phase128.png` to `/usr/share/pixmaps`

phase-qt.protocol (KDE)

