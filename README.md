usmartmount
===========

A udev script set for auto-mounting usb drives

Features
========

1. Mount on plug-in and umount on removal.
2. Mount point based on label and UUID.
3. Use mount(8) for fat (to avoid latin-1 iocharset), mount.exfat(8) for exfat and pmount(1) for others.
