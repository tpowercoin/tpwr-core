
Debian
====================
This directory contains files used to package tpwrd/tpwr-qt
for Debian-based Linux systems. If you compile tpwrd/tpwr-qt yourself, there are some useful files here.

## tpwr: URI support ##


tpwr-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tpwr-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tpwrqt binary to `/usr/bin`
and the `../../share/pixmaps/tpwr128.png` to `/usr/share/pixmaps`

tpwr-qt.protocol (KDE)

