
Debian
====================
This directory contains files used to package improvedbitcoind/improvedbitcoin-qt
for Debian-based Linux systems. If you compile improvedbitcoind/improvedbitcoin-qt yourself, there are some useful files here.

## improvedbitcoin: URI support ##


improvedbitcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install improvedbitcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your improvedbitcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/improvedbitcoin128.png` to `/usr/share/pixmaps`

improvedbitcoin-qt.protocol (KDE)

