# Hackintosh-Bootloader-for-B150-RX570

Default settings: iMac18,2, No GUI, No Picker, HiDPI (2x), Power Nap On (darkwake=10)

macOS Version: Catalina 10.15.5

| Hardware | Model |
| --- | --- |
| CPU | i3-6100 (XCPM+HWP by CPUFriend) |
| GPU | Intel HD Graphic 530 (no-connector, ig-platform-id: 0x19120001) + Sapphire AMD RX470D (VBIOS RX570, PCI-e Slot-1) |
| SSD | Apple SSD SM0128G (M.2 in use) |
| Memory | DDR4 2400 8GB (Running at 2133 MHz, BANK0/DIMM0) |
| Soundcard | Onboard Realtek ALC1150 (alc-layout-id: 3) |
| Motherboard | ASUS B150 PRO GAMING (Latest UEFI BIOS) |
| Wi-Fi Card | Apple BCM943602CDP (4 antennas, 802.11a/b/g/n/ac, Simultaneous dual band (2.4GHz & 5GHz), HT80 with 3x3 MIMO, used by iMac Intel 21.5” or 27” (Mid 2015-Late 2015)) |

## Not Work
### OpenCore
No Problem!

----------

Update 2020-07-01: Disable Fast Boot in UEFI BIOS

It may break your UEFI BIOS, but you can reset nvram to resolve it

### Clover
Sidecar or DRM

If you add shikigva=80 to boot-args, Sidecar works but not perfect (frame blur), DRM OK.

Or do not do anything, use default config, Sidecar works perfect, but DRM doesn't work.
