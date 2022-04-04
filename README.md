# pixel-experience
Instruction manual to enjoy `Pixel Experience` on supported xiaomi phones.

- Download bootloader img and recovery zip from the website.
- Press Volume Down and Power Button to turn the cellphone to fastboot mode.
- To check fastboot device run `fastboot devices` to get a unique id of the connected device.
- Now `fasboot boot <boot-image-path>` to boot to pixel experience based bootloader.
- Now navigate to adb methord of sideloading recovery zip.
- Type  `ad sideload <path-to-zip>` to install the rom.
