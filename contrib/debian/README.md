
Debian
====================
This directory contains files used to package infinitemoneycoind/infinitemoneycoin-qt
for Debian-based Linux systems. If you compile infinitemoneycoind/infinitemoneycoin-qt yourself, there are some useful files here.

## infinitemoneycoin: URI support ##


infinitemoneycoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install infinitemoneycoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your infinitemoneycoinqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

infinitemoneycoin-qt.protocol (KDE)

