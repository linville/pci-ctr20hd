# Measurement Computing PCI-CTR20HD Kernel Driver
This is a minimal fork of the original loadable kernel module for the Measurement Computing pci-ctr20hd counter timer board developed by Warren Jasper. The pci-ctr20hd has four CTS9513 chips (AM9513 compatible) which provide for a total of 5, 16-bit programmable up/down counters.

See the [Readme](README) from the original distribution for more details and usage on the driver.

# Changes
* Added support for blocking ioctl commands.
* Minor comment / documentation fixes.

# License
GPLv2. See the [License](License) file for details.
