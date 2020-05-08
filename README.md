# xorg-debug
Guadalinex Construction System package to use gdb to debug Xorg crashes.

This package installs the Xdebug bash scripts that must be run as root and this script runs gdb attaching it to the Xorg server.

This package also introduces lines in /etc/sudoers file so Xdebug can be run with sudo, and introduces a Xdebug.desktop file inside /etc/xdg/autostart so the Xdebug script is run 30 seconds after starting a Xorg session.

The gdb logs are located in /var/log/gdb*


