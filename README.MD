EFI for Lenovo E15 Gen 4 - Full Acceleration - 1235U/Iris Xe

*Installing*

1. Once you've prepared installation media, mount yout EFI partition and copy this folder
2. Remove config.plist and set aside. rename config-install.plist to config.plist and boot into USB
3. Once you've installed Tahoe, you need to install the modified nootedgreen

4. Follow installation instructions here
https://github.com/JulioNectar/Hackintosh-XPS13Plus-IrisXe-Tahoe/blob/main/docs/INSTALL.md

Credit: Julian Nectar 

This walks through how to enable the modified drivers and full acceleration.

5. Once install is complete, replace the 'config-install'.plist with the config.plist set aside. Reset NVRAM and reboot.

Notes:
Brightness doesn't adjust, sleep is not possible but patches are being worked on. No 'Night-Mode' ability at present. There's some choppiness in preview and photos. 

Working: Audio , Bluetooth, Wifi, Webcam, iCloud

I'd recommend updating the SMBIOS platform with new serials as also mentioned in JulioNectar's instructions. Macbook 16,3 