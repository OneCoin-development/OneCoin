
Debian
====================
This directory contains files used to package oned/one-qt
for Debian-based Linux systems. If you compile oned/one-qt yourself, there are some useful files here.

## one: URI support ##


one-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install one-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your one-qt binary to `/usr/bin`
and the `../../share/pixmaps/one128.png` to `/usr/share/pixmaps`

one-qt.protocol (KDE)

