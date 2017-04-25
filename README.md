Own ArchIso
===========

  This is my own archiso build script, based on `/usr/share/archiso/configs/releng`.


Changes
-------

   1. zfs ready. If needed, run `modprobe zfs`;
   2. make use of `neovim` instead of `vim`;
   3. copy the following settings from the host to airootfs:
     - /etc/localtime
     - /etc/pacman.conf
     - /etc/pacman.d/*mirrorlist
     - /etc/locale.gen


TODO
----

   1. export lists of installed packages for each repository, and AUR;
