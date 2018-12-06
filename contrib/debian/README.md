
Debian
====================
This directory contains files used to package cryptocoupond/cryptocoupon-qt
for Debian-based Linux systems. If you compile cryptocoupond/cryptocoupon-qt yourself, there are some useful files here.

## cryptocoupon: URI support ##


cryptocoupon-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cryptocoupon-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cryptocouponqt binary to `/usr/bin`
and the `../../share/pixmaps/cryptocoupon128.png` to `/usr/share/pixmaps`

cryptocoupon-qt.protocol (KDE)

