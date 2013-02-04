![dosfstools logo](https://raw.github.com/Godzil/dosfstools/master/dosfstools.png) dosfstools
=============================================================================================

* * *

About
-----

**dosfstools** contains utilities for making and checking MS-DOS FAT filesystems.

The dosfstools package includes the mkdosfs (aka mkfs.dos and mkfs.vfat) and dosfsck (aka fsck.msdos and fsck.vfat) utilities, which respectively make and check MS-DOS FAT filesystems on hard drives or on floppies.

This version uses the enhanced boot sector/superblock format of DOS 3.3+ as well as provides a default dummy boot sector code.

I made this fork to add support for some options that are missing for my own need like the "-C" option found on other fsck utilities.

Official dosfstools is currently maintained by Daniel Baumann mail@daniel-baumann.ch, dba on irc.oftc.net. You can found it [here](http://www.daniel-baumann.ch/software/dosfstools/).
