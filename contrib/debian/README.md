
Debian
====================
This directory contains files used to package collectiblecoind/collectiblecoin-qt
for Debian-based Linux systems. If you compile collectiblecoind/collectiblecoin-qt yourself, there are some useful files here.

## collectiblecoin: URI support ##


collectiblecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install collectiblecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your collectiblecoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/collectiblecoin128.png` to `/usr/share/pixmaps`

collectiblecoin-qt.protocol (KDE)

