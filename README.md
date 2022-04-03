# Jetson Nano kernel builder

This is a Docker container that can be used to build a custom Jetson Nano
Linux Kernel.

The `Dockerfile` included will build the kernel with config settings and
a patch required to make iPhone USB Tethering work.

*Note:* This is a work in progress and requires understanding of what's
going on to do anything with it right now.


## Useful References

* [Jetson instructions for building a kernel](https://docs.nvidia.com/jetson/archives/l4t-archived/l4t-3261/index.html#page/Tegra%20Linux%20Driver%20Package%20Development%20Guide/kernel_custom.html)
* [Gentoo instructions for iPhone Tethering](https://wiki.gentoo.org/wiki/Iphone_USB_tethering) (mentions needing to enable `USB_IPHETH` in the kernel)
* [Kernel patch for iPhone tethering](https://github.com/torvalds/linux/commit/63e4b45c82ed1bde979da7052229a4229ce9cabf)
