
Debian
====================
This directory contains files used to package bitcoinclassicd/bitcoinclassic-qt
for Debian-based Linux systems. If you compile bitcoinclassicd/bitcoinclassic-qt yourself, there are some useful files here.

## bitcoinclassic: URI support ##


bitcoinclassic-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitcoinclassic-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitcoinclassic-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoinclassic128.png` to `/usr/share/pixmaps`

bitcoinclassic-qt.protocol (KDE)

