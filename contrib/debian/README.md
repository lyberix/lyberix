
Debian
====================
This directory contains files used to package lyberixv3d/lyberixv3-qt
for Debian-based Linux systems. If you compile lyberixv3d/lyberixv3-qt yourself, there are some useful files here.

## lyberixv3: URI support ##


lyberixv3-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lyberixv3-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lyberixv3qt binary to `/usr/bin`
and the `../../share/pixmaps/lyberixv3128.png` to `/usr/share/pixmaps`

lyberixv3-qt.protocol (KDE)

