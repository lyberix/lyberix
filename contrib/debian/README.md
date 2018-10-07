
Debian
====================
This directory contains files used to package lyberixd/lyberix-qt
for Debian-based Linux systems. If you compile lyberixd/lyberix-qt yourself, there are some useful files here.

## lyberix: URI support ##


lyberix-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lyberix-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lyberixqt binary to `/usr/bin`
and the `../../share/pixmaps/lyberix128.png` to `/usr/share/pixmaps`

lyberix-qt.protocol (KDE)

