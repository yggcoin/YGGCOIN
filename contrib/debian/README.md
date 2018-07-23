
Debian
====================
This directory contains files used to package yggd/ygg-qt
for Debian-based Linux systems. If you compile yggd/ygg-qt yourself, there are some useful files here.

## ygg: URI support ##


ygg-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ygg-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your yggqt binary to `/usr/bin`
and the `../../share/pixmaps/ygg128.png` to `/usr/share/pixmaps`

ygg-qt.protocol (KDE)

