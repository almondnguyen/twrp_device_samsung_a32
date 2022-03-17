## Recovery Device Tree for the Samsung Galaxy A32 4G (MTK)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_a32-eng
make recoveryimage
```

Based on:
> https://github.com/mohammad92/android_device_samsung_a32x

Blobs version:
> Kernel base: A325FXXU1AUB5,
> Ramdisk, DTB, DTBO base: A325FXXU2AUJ4

Kernel source:
> https://github.com/almondnguyen/android_kernel_samsung_a32/tree/r
