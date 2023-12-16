This is repo contains efi file for Lenovo Thinkpad X270:

## Spec

💻 Laptop: 
- Merk: Lenovo Thinkpad x270
- Processor: i5-6300U (Skylake-U)
- igpu: Intel(R) HD Graphics 520
- RAM: 16GB DDR4 2133 Mhz
- Audio: Realtek ALC298 @ Intel Sunrise Point-LP PCH - High Definition Audio Controller
- Trackpad: HID-Compilant Mouse
- Storage : SSD SATA 128 + 128 GB
- Wireless + bluetooth : Intel(R) Dual Band Wireless-AC 8260
- Ethernet: Intel(R) Ethernet Connection I219-LM
- Bootloader: Opencore 0.9.7
- OS Version: MacOS monterey 12.7.2
- Installer offline: olarilla

## Customization

Custom command for fix lagging when maximize and minimize window:

`defaults write -g NSWindowResizeTime -float 0.001`
 
To restore animation time you must use this command:

`defaults delete -g NSWindowResizeTime`

Thanks ☕
