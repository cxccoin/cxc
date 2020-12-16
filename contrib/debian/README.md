
Debian
====================
This directory contains files used to package koipayd/koipay-qt
for Debian-based Linux systems. If you compile koipayd/koipay-qt yourself, there are some useful files here.

## koipay: URI support ##


koipay-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install koipay-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your koipayqt binary to `/usr/bin`
and the `../../share/pixmaps/koipay128.png` to `/usr/share/pixmaps`

koipay-qt.protocol (KDE)

