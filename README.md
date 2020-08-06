=== Freon build script ===

Simple script that, as of right now, builds Freon Linux distribution that is shipped with glibc, busybox, and a hand full of other utilities.

Changelog:
 * v0.4.2: Adding some functionality to thaw (package manager). Using TinyCoreLinux 9.x package repository for some extension to the OS without bloating the disk size.  
 * v0.4.1: Added a couple of utilities to build-extensions. dropbear SSH2 client, htop, as well as reconfiguring chttpd for web hosting.
 * v0.4.0: 
	Freon Linux is now functional with the capabilities of installing on most hardware. Kernel is mostly static, no modules for devices.
	Also included the following updates: kernel-5.1.12 update, liblzma is built in for grub2, and some software added in build-extensions.
 * v0.3.0: Taking a new route with Freon, and now making it a standalone distribution for embedded servers.
 * v0.2.1b: Added build-pkg, in dev. Successfully builds TCC for Freon's package manager.
 * v0.2.1: Update: Linux kernel 4.19, GNU C library 2.28. Functioning x64 builds, with built-in onboard network drivers.
 * v0.2.0: Major update, added refer feature. Rebuilds rootfs with freon scripts. Linux headers no longer shipped with finished ISO.
 * v0.1.0: Name change and overhaul. Now Freon build script.
 * v0.0.2: Still basic, working on 64 bit host systems, generated box working.
 * v0.0.1: Simple, --verbose added, not fully working

This software is released under the GPLv3 and is to be used "as is". There is no warranty with this software and is to be used by an experienced GNU/Linux developer.
