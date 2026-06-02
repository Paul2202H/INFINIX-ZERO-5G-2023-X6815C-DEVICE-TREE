# CUSTOM RECOVERY DEVICE TREE FOR INFINIX ZERO 5G 2023 ( X6815C )

# Device SPecifications
Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core (2x2.6 GHz Cortex-A78 & 6x2.0 GHz Cortex-A55)
Chipset | MediaTek Dimensity 1080 (MT6877)
GPU     | Mali-G68 MC4
Memory  | 8 GB RAM
Shipped Android Version | 12
Storage | 256 GB (UFS)
Battery | 5000 mAh, non-removable
Display | 1080 x 2460 pixels,6.8 inches, 60/90/120hz

# picture
![infinixzero5g2023](https://fdn2.gsmarena.com/vv/pics/infinix/infinix-zero-5g-2023-turbo-2.jpg)

# Checks
Blocking checks
- [✔] Correct screen/recovery size
- [✔] Working Touch, screen
- [✔] Backup to internal/microSD
- [✔] Restore from internal/microSD
- [✔] reboot to system
- [✔] ADB

Medium checks
- [✔] update.zip sideload
- [✔] UI colors (red/blue inversions)
- [✔] Screen goes off and on
- [✔] F2FS/EXT4 Support, exFAT/NTFS where supported
- [✔] all important partitions listed in mount/backup lists
- [✔] backup/restore to/from external (USB-OTG) storage
- [?] backup/restore to/from adb (https://gerrit.omnirom.org/#/c/15943/)
- [✔] decrypt /data
- [✔] Correct date

Minor checks
- [✔] MTP export
- [✔] reboot to bootloader
- [✔] reboot to recovery
- [✔] poweroff
- [✔] battery level
- [✔] temperature
- [?] encrypted backups
- [✔] encrypted backups
- [✔] input devices via USB (USB-OTG) - keyboard and mouse
- [✔] USB mass storage export
- [✔] set brightness
- [?] vibrate
- [✔] screenshot
- [✔] partition SD card
- [✔] Fastbootd

