Calcus: the basics
==================

Calcus is the computational server. It runs Linux and has a processor with 16 cores.

SSH (connecting remotely)
-------------------------

To connect to calcus, you will be using ssh (secure shell)::
  
  ssh username@192.168.199.58

Drives
------
There are two storage pools:

1. HDD (7.3 TB) - your home folder lives here
2. SSD (1.3 TB) accessible under ``/opt/ssd/`` - smaller but faster, this is for data actively used in analyses

The ``/opt/ssd/`` is a shared space. Please keep your files under ``/opt/ssd/username`` and use it only for files which you really need to access quickly.

Also, please treat disk space like a finite resource!

Your files are visible to other users, but don't worry, they cannot modify or remove them - Linux has a strong concept of users and file ownership.
