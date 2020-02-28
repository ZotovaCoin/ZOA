
Debian
====================
This directory contains files used to package zotovad/zotova-qt
for Debian-based Linux systems. If you compile zotovad/zotova-qt yourself, there are some useful files here.

## zotova: URI support ##


zotova-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zotova-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zotovaqt binary to `/usr/bin`
and the `../../share/pixmaps/zotova128.png` to `/usr/share/pixmaps`

zotova-qt.protocol (KDE)

