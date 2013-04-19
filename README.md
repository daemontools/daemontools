How to install daemontools
==========================

Like any other piece of software (and information generally), daemontools comes with NO WARRANTY.


System requirements
-------------------


daemontools works only under UNIX.


Installation
------------

Create a /package directory:
     mkdir -p /package
     chmod 1755 /package
     cd /package

Download daemontools-0.76.tar.gz into /package. Unpack the daemontools package:
     gunzip daemontools-0.76.tar
     tar -xpf daemontools-0.76.tar
     rm -f daemontools-0.76.tar
     cd admin/daemontools-0.76

Compile and set up the daemontools programs:
     package/install

On BSD systems, reboot to start svscan.

--------------------------------------------------------------------------------

To report success:
     mail djb-sysdeps@cr.yp.to < /package/admin/daemontools/compile/sysdeps

