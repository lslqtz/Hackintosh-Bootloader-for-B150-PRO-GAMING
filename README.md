# Hackintosh-Bootloader-for-B150-RX570

CPU: i3-6100 (XCPM+HWP by CPUFriend)

GPU: Sapphire AMD RX470D (VBIOS RX570)

Memory: DDR4 2400 8GB (Running at 2133 MHz, PCI-e Slot-1)

Motherboard: ASUS B150 PRO GAMING (Latest UEFI BIOS)

## Not Work
### OpenCore
Everything is right!

### Clover
Sidecar or DRM

If you add shikigva=80 to boot-args, Sidecar works but not perfect (frame blur), DRM OK.

Or do not do anything, use default config, Sidecar works perfect, but DRM doesn't work.
