zfs-stats
=============

ZFS statistics tool for Linux.

The zfs-stats script displays general ZFS information
and human-readable ZFS statistics of the following subsystems:

* ARC
* L2ARC
* DMU (zfetch)
* vdev cache

The script is a fork of Martin Matuška' [zfs-stats for FreeBSD][1] which 
in turn is a port of Jason J. Hellenthals' [arc_summary.pl][2]

Use the customised [linux-kstat][3] Perl module.

Memory information has not fully been updated and sysctl ZFS tunables have been disabled.

[1]: https://github.com/mmatuska/zfs-stats
[2]: http://code.google.com/p/jhell/
[3]: https://github.com/pimlie/linux-kstat
