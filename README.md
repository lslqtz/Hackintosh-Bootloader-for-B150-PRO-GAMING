# Hackintosh-Bootloader-for-B150-RX570

CPU: i3-6100 (XCPM+HWP by CPUFriend)

GPU: Intel HD Graphic 530 (ig-platform-id: 0x19120001) + Sapphire AMD RX470D (VBIOS RX570, PCI-e Slot-1)

Memory: DDR4 2400 8GB (Running at 2133 MHz, BANK0/DIMM0)

Motherboard: ASUS B150 PRO GAMING (Latest UEFI BIOS)

Wi-Fi Card: Apple BCM943602CDP (802.11a/b/g/n/ac, 2.4GHz/5GHz HT80, 3x3 MIMO)

## Not Works
### OpenCore
It may break your UEFI BIOS, but you can reset nvram to resolve it

### Clover
Sidecar or DRM

If you add shikigva=80 to boot-args, Sidecar works but not perfect (frame blur), DRM OK.

Or do not do anything, use default config, Sidecar works perfect, but DRM doesn't work.
