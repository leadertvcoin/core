
Debian
====================
This directory contains files used to package leadertvcoind/leadertvcoin-qt
for Debian-based Linux systems. If you compile leadertvcoind/leadertvcoin-qt yourself, there are some useful files here.

## leadertvcoin: URI support ##


leadertvcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install leadertvcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your leadertvcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/leadertvcoin128.png` to `/usr/share/pixmaps`

leadertvcoin-qt.protocol (KDE)

