
Debian
====================
This directory contains files used to package arkoscoind/arkoscoin-qt
for Debian-based Linux systems. If you compile arkoscoind/arkoscoin-qt yourself, there are some useful files here.

## arkoscoin: URI support ##


arkoscoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install arkoscoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your arkoscoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/arkoscoin128.png` to `/usr/share/pixmaps`

arkoscoin-qt.protocol (KDE)

