MySQL Tools
===========

Tools for administering daily task regarding MySQL.

1) Clone repository
-------------------

    git clone git@github.com:staticsirupflo/mysql-tools.git

2) Copy config
--------------

Copy mysql-backup.cfg.dist to mysql-backup.cfg and fill in your settings. The cfg file has to be passed as argument.

3) Example

    /usr/local/bin/mysql-backup.sh /home/me/mysql-backup.cfg

Tested under
------------

 * OSX
 * Linux (Debian tested)
 
Notes & credits
---------------

The mysql-backup.sh is heavily based on the work of Matt Reid from kontrollsoft. See comments in file.

TBD
---
 * Rework code a bit more.