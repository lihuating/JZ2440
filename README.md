# JZ2440
The project just use for JZ2440 to learn and practice.

uboot :not for jz2440 ,org version
kernel: unkown
busybox: unkown




uboot usage:

tar xjf u-boot-1.1.6.tar.bz2
cd u-boot-1.1.6
patch -p1 < ../u-boot-1.1.6_jz2440_burn_nor_with_nand_uboot.patch
make 100ask24x0_config
make 

//重新烧写u-boot.bin



kernel usage:
make uImage






