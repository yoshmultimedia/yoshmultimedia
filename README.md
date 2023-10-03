- 👋 Hi, I’m @yoshmultimedia
- whatsapp 082223330338
- [yoshmultimedia/yoshmultimedia](https://www.youtube.com/@yoshmultimedia)
-cd /storage/self/primary
-dd if=sec_efs.bin of=/dev/block/sda2
-dd if=efs.bin of=/dev/block/sda1
-lun0
-sda1 /user_part/efs.img /debug_ramdisk/.magisk/mirror/mnt/vendor/efs
-sda2 /user_part/efs.img  /debug_ramdisk/.magisk/mirror/efs
-lun3
-sdd
--sdd1 cpefs /user_part/cpefs.img


