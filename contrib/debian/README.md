
Debian
====================
This directory contains files used to package brnd/brn-qt
for Debian-based Linux systems. If you compile brnd/brn-qt yourself, there are some useful files here.

## brn: URI support ##


brn-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install brn-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your brnqt binary to `/usr/bin`
and the `../../share/pixmaps/brn128.png` to `/usr/share/pixmaps`

brn-qt.protocol (KDE)

