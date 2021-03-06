---
title: DragonBoard 820c OpenEmbedded
permalink: /documentation/consumer/dragonboard820c/downloads/open-embedded.md.html
---
# OpenEmbedded

**OpenEmbedded** is a software framework used for creating Linux distributions aimed for, but not restricted to, embedded devices. Below are pre-built console and desktop images of Debian with their respective bootloader and boot image. If desired, these images can be recreated by following the build from source instructions found [here](https://github.com/Linaro/documentation/blob/master/Reference-Platform/CECommon/OE.md) (Note: this link will take you to the Linaro Github)

***

## Fastboot files (Advanced users)

|   Bootloader    |    Download    |
|:------------------|:-----------------------|
|Release Notes:     |[Link](http://builds.96boards.org/releases/dragonboard410c/linaro/rescue/latest/)      |

Choose one boot image, the root file system you choose will be based on the boot image you download here:

|   Boot image    |  Build Folder ([RPB](http://builds.96boards.org/releases/reference-platform/openembedded/dragonboard410c/latest/rpb/) / [RPB-Wayland](http://builds.96boards.org/releases/reference-platform/openembedded/dragonboard410c/latest/rpb-wayland/))   |
|:------------------|:-----------------------|
| RPB    | Download   |
| RPB-Wayland    |  Download  |

Only download one root file system (Console or Desktop). You should match the type of rootfs to the boot image you downloaded above.

|   Rootfs image    |  Build Folder ([RPB](http://builds.96boards.org/releases/reference-platform/openembedded/dragonboard410c/latest/rpb/) / [RPB-Wayland](http://builds.96boards.org/releases/reference-platform/openembedded/dragonboard410c/latest/rpb-wayland/))    |
|:------------------|:----------------------------------|
| RPB  | (Download / [Download)    |
| RPB-Wayland  | (Download / Download)     |

Continue to [Installation page](../installation)
