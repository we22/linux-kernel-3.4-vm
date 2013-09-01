linux-kernel-3.4-vm
===================

Linux 3.4 branch kernel config for Xen virtual machine

Current kernel version: 3.2.60

Main Features:
- Xen frontend
- cgroup
- iSCSI
- ext4
- LVM
- iptables
- ipset
- ipv6

Compile options:

    export CHOST="i686-pc-linux-gnu"
    export CFLAGS="-march=native -O2 -pipe -fomit-frame-pointer"
    export CXXFLAGS="${CFLAGS}"

Kernel command line parameters:

    nmi_watchdog=0 cgroup_disable=memory
