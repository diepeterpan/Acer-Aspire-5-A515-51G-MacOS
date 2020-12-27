# Acer-Aspire-5-A515-51G-MacOS-Big-Sur
Use this OpenCore EFI to run MacOS Big Sur on Acer Aspire 5 A515-51G (2018) 

## Configuration

| Specifications | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Computer model      | Acer Aspire 5 A515-51G (2018)      |
| Processor           | Intel Core i5-8250U     |
| Memory              | 8GB/20GB  DDR4 2400MHz              |
| Hard Disk           | Only tested with SATA SSD    |
| Integrated Graphics | Intel UHD Graphics 620                     |
| Monitor             | FHD 1920x1080 (15 inch) |
| Sound Card          | Realtek ALC255           |
| Wireless Card       | Swapped                     |
| SD Card Reader      | Realtek PCI                 |


## Current Status

- **NVIDIA MX150** is not working

- Everything else works well

- Brightness keys working 100% with normal brightness keys
  
- Ensure to edit the **config.plist** and add valid  **PlatformInfo Generic** and **SMBIOS** values

- Install **Captin.dmg** to have a Caps Lock indicator on screen

- Install **ComboJack** to assist with Headphones / Headset

- **Apple Watch** unlock is not consitant but seems to be a generic problem on hackintoshes

- **2.4 GHz Wifi interference** with Bluetooth (mostly Bluetooth audio) also seems to be a common problem
