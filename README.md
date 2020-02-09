# UBports GH Actions
This repository enables images to be built from GitHub Actions.

## Building Status:  
|                 Ubuntu Touch 7.1          |                  Ubuntu Touch 5.1                    | 
|:------------:|:------------:|
| ![Build System Image](https://github.com/ubports-onyx/ubports-ci/workflows/Build%20System%20Image/badge.svg?branch=ut-7.1) |        ![Build System Image](https://github.com/ubports-onyx/ubports-ci/workflows/Build%20System%20Image/badge.svg?branch=ut-5.1)   |
| [Download](https://github.com/ubports-onyx/ubports-ci/actions) | [Download](https://github.com/ubports-onyx/ubports-ci/actions)                    | 

### What working or Missing:  
|            |      Ubuntu Touch 7.1          |                   Ubuntu Touch 5.1                    | 
|:------------:|:------------:|:------------:|
| Ril | [x]    | [x]   |
| Sound | [x]    | [x]   |
| Touch | [x]    | [x]   |
| Wifi | [x]    | [x]   |
| GPS | [x]    | [ ]   |
| Vibration | [x]    | [x]   |
| Orientation sensor | [x]    | [x]   |
| Anbox | [ ]    | [x]   |
| Bluetooth | [x]    | [x]   |
| Flash light | [x]    | [x]   |
| MTP | [ ]    | [x]   |
| Libertine | [ ]    | [ ]   |
| camera | [ ]    | [ ]   |
| notification lights | [*]    | [*]   |
| Hotspot | [ ]    | [ ]   |
| apparmor | [ ]    | [ ]   |
| Light Sensor | [ ]    | [ ]   |
| Battery | [ ]    | [ ]   |
| Light Sensor | [ ]    | [ ]   |
| Light Sensor | [ ]    | [ ]   |
| more |  ...    | ...   |

### Install:  
   * Prerequisites: Unlocked bootloader , PC
   * TWRP from Official Twrp site and flash it into your OneplusX
   * You need system.img , halium-boot and latest ubports-touch rootfs
   * Download system & halium-boot from [here](https://github.com/ut-on-garlic/ubports-ci)
   * Download [ubports-touch.rootfs-xenial-armhf.tar.gz](https://ci.ubports.com/job/xenial-rootfs-armhf/)
   * Clone or download the [halium-install repository](https://gitlab.com/JBBgameich/halium-install)
   * reboot your phone to TWRP and  wipe Data partitions and make sure partitions are ext4
   * do "path/to/halium-install -p ut path/to/rootfs.tar.gz path/to/system.img"
   * Enjoy  
More detail about install ubuntu touch in [here](http://docs.ubports.com/en/latest/porting/installing-16-04.html#installing-ubuntu-touch-16-04-images-on-halium) 
    
