# RSKSevenProject Kernel for ASUS ZenFone Max Pro M1 (X00TD)

Custom 4.4 kernel with overclocking (2.46GHz CPU, 750MHz GPU), KernelSU-Next support, optimized for Android 10.

## Device
- ASUS ZenFone Max Pro M1 (X00TD)
- Snapdragon 636 (SDM660)

## Base
- LineageOS/android_kernel_asus_sdm660 (branch lineage-18.1)

## Features
- Overclocking (dalam pengembangan): CPU big 2.46GHz (+11 persen), GPU 750MHz (+15 persen)
- KernelSU-Next (dalam pengembangan): root via KernelSU-Next dengan manual hook untuk kernel 4.4
- Branding: RSKSevenProject (4.4.261-RSKSevenProject)
- Varian: NLV (non-LED vibration) untuk Android 10

## Status
DALAM PENGEMBANGAN - versi saat ini bootloop, jangan pakai untuk daily use.

## Cara Build
    make O=out ARCH=arm64 X00TD_defconfig
    make O=out ARCH=arm64 -j3 CROSS_COMPILE=aarch64-linux-gnu- CROSS_COMPILE_ARM32=arm-linux-gnu-

Hasil: out/arch/arm64/boot/Image.gz-dtb

## Credit
- LineageOS - base kernel source
- osm0sis - AnyKernel3 (xda-developers)
- KernelSU-Next team - KernelSU-Next

## License
GPLv2 - sesuai lisensi kernel Linux.
