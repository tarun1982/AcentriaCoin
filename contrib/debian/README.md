
Debian
====================
This directory contains files used to package acentriacoind/acentriacoin-qt
for Debian-based Linux systems. If you compile acentriacoind/acentriacoin-qt yourself, there are some useful files here.

## acentriacoin: URI support ##


acentriacoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install acentriacoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your acentriacoinqt binary to `/usr/bin`
and the `../../share/pixmaps/acentriacoin128.png` to `/usr/share/pixmaps`

acentriacoin-qt.protocol (KDE)

