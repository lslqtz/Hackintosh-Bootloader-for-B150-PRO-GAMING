# Hackintosh-Bootloader-for-B150-RX570

Default settings: iMac18,2, No GUI, No Picker, HiDPI (2x), Power Nap On (darkwake=10)

macOS Version: Catalina 10.15.5

CPU: i3-6100 (XCPM+HWP by CPUFriend)

GPU: Intel HD Graphic 530 (ig-platform-id: 0x19120001) + Sapphire AMD RX470D (VBIOS RX570, PCI-e Slot-1)

Memory: DDR4 2400 8GB (Running at 2133 MHz, BANK0/DIMM0)

Soundcard: Onboard Realtek ALC1150 (alc-layout-id: 3)

Motherboard: ASUS B150 PRO GAMING (Latest UEFI BIOS)

Wi-Fi Card: Apple BCM943602CDP (802.11a/b/g/n/ac, 2.4GHz/5GHz HT80, 3x3 MIMO)

## Not Work
### OpenCore
It may break your UEFI BIOS, but you can reset nvram to resolve it
Update 2020-06-16: I think it's ok now

### Clover
Sidecar or DRM

If you add shikigva=80 to boot-args, Sidecar works but not perfect (frame blur), DRM OK.

Or do not do anything, use default config, Sidecar works perfect, but DRM doesn't work.
