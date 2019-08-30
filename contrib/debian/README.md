
Debian
====================
This directory contains files used to package escortcoind/escortcoin-qt
for Debian-based Linux systems. If you compile escortcoind/escortcoin-qt yourself, there are some useful files here.

## escortcoin: URI support ##


escortcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install escortcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your escortcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/escortcoin128.png` to `/usr/share/pixmaps`

escortcoin-qt.protocol (KDE)

