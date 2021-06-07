# Big Sur 11.4 hackintosh for Acer E 15 (E5-571-5552)

Hardware:
* Intel Haswell i5-4210U
* HD4400
* Sata SSD
* ALC283 Audio card
* Realtek RTL8111 Ethernet card
* Realtek RTL8411B Card Reader
* WIFI and Bluetooth AC7260 (I upgraded WIFI card)
* Webcam USB internal

Almost everything works, including the hardware listed above, sleep, volume and brightness adjustment keys, except for:
* Sound through HDMI (video works)
* hibernation (sleep works)

The installation uses OC 069. There is no tweaks to the Mac OS system files. Copy the `everything works EFI` to the EFI partition. OC should handle everything. 

### Troubleshooting
* To display the boot selection menu, change the OC/config.plist `ShowPicker` to true.
* My headphone volume is low, adjust the audio settings in `Audio MIDI Setup` like what the `enable headphone sound` image shows.
* Sleep need some setting in the sytem. Follow the `fix sleep` in `guideliens` dir.

GLHF
