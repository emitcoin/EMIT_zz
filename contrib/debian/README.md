
Debian
====================
This directory contains files used to package emitd/emit-qt
for Debian-based Linux systems. If you compile emitd/emit-qt yourself, there are some useful files here.

## emit: URI support ##


emit-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install emit-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your emitqt binary to `/usr/bin`
and the `../../share/pixmaps/emit128.png` to `/usr/share/pixmaps`

emit-qt.protocol (KDE)

