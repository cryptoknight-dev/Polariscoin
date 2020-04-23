
Debian
====================
This directory contains files used to package polariscoind/polariscoin-qt
for Debian-based Linux systems. If you compile polariscoind/polariscoin-qt yourself, there are some useful files here.

## polariscoin: URI support ##


polariscoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install polariscoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your polariscoinqt binary to `/usr/bin`
and the `../../share/pixmaps/polariscoin128.png` to `/usr/share/pixmaps`

polariscoin-qt.protocol (KDE)

