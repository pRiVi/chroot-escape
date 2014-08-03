chroot-escape
=============

Let you escape from a linux chroot.

Works only if you're root in the chroot.

This is a POSIX specification bug, which is not fixed in linux since years: chroot must go up a directory if you're outside the chrooted or not.

