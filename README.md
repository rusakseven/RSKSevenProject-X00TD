# RSKSevenProject Kernel for ASUS ZenFone Max Pro M1 (X00TD)

Custom kernel for ASUS ZenFone Max Pro M1 (X00TD, Snapdragon 636).

## Base

- RyuujiX/android_kernel_asus_sdm660 (branch r7/hmp)
- Linux 4.4.302

## Features

- **Overclocking**: CPU big up to 2.46GHz, GPU up to 750MHz (Extreme variant)
- **KernelSU-Next v3.2.0**: root via KernelSU-Next with manual hooks for kernel 4.4
- **SCHED_HMP**: proper big.LITTLE scheduler support
- **Branding**: RSKSevenProject (4.4.302-RSKSevenProject)
- **Variants**: NLV (non-LED vibration) for Android 10
- **CPU Governors**: 16 governors (blu_active, alucard, zzmoove, etc.)
- **I/O Schedulers**: 13 schedulers (anxiety, maple, zen, etc.)
- **KCAL**: display color calibration
- **WireGuard**: modern VPN support
- **Boeffla Wakelock Blocker**: battery saving

## Variants

| Variant | CPU Max | GPU Max | Use Case |
|---------|---------|---------|----------|
| Stock | 1.96GHz | 585MHz | Daily, cool |
| OC | 2.2GHz | 585MHz | Balanced |
| Extreme | 2.46GHz | 750MHz | Full OC |

## Status

**STABLE** - Tested on Nusantara Android 10 (NLV). Bluetooth, WiFi, and app installation working.

## Downloads

[GitHub Releases](https://github.com/rusakseven/RSKSevenProject-X00TD/releases/tag/v1.0-stock-extreme-20261007)

## Credits

- Base: RyuujiX
- KernelSU-Next: KernelSU-Next team
