# RSKSevenProject Kernel for ASUS ZenFone Max Pro M1 (X00TD)

Custom kernel for ASUS ZenFone Max Pro M1 (X00TD, Snapdragon 636).

## Base

- RyuujiX/android_kernel_asus_sdm660 (branch r7/hmp)
- Linux 4.4.302

## Features

- **Overclocking**: CPU big up to 2.46GHz, GPU up to 750MHz (Extreme variant)
- **KernelSU-Next v3.2.0-legacy (33129) + SuSFS v2.3.0**: root via KernelSU-Next with manual hooks for kernel 4.4
- **SCHED_HMP**: proper big.LITTLE scheduler support
- **Branding**: RSKSevenProject (4.4.302-RSKSevenProject)
- **Variants**: NLV (Android 10) and LV (Android 11/12), each in Stock/OC/Extreme
- **CPU Governors**: 16 governors (blu_active, alucard, zzmoove, etc.)
- **I/O Schedulers**: 13 schedulers (anxiety, maple, zen, etc.)
- **KCAL**: display color calibration
- **WireGuard**: modern VPN support
- **Boeffla Wakelock Blocker**: battery saving

## Variants

| Variant | CPU Max | GPU Max | Use Case |
|---------|---------|---------|----------|
| Stock | 1.96GHz | 430MHz | Daily, cool |
| OC | 2.2GHz | 585MHz | Balanced |
| Extreme | 2.46GHz | 750MHz | Full OC |

Each variant ships as **NLV** (Android 10) and **LV** (Android 11/12) - pick the one matching your ROM, the wrong variant means no vibration. All variants include KernelSU-Next v3.2.0-legacy + SuSFS v2.3.0.

## Status

**Stock variants tested on device** (NLV on Android 10, LV on Android 11 - boot, root, SuSFS, vibration and module auto-service verified). OC (GPU 585MHz rebuild) and Extreme are **awaiting on-device testing**.

## Downloads

[GitHub Releases](https://github.com/rusakseven/RSKSevenProject-X00TD/releases/tag/v1.1-matrix-20261009)

## Credits

- Base: RyuujiX
- KernelSU-Next: KernelSU-Next team
