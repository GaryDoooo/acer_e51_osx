# Serria hackintosh for Acer E 15 (E5-571-5552)

Initial steps could follow the guide in https://github.com/GalaticStryder/Acer-E5-571-Hackintosh

1. Follow the guide until extracted the DSL files from the bios; (the dsdt files were extracted under Linux.)
2. Use the all in one patch files to patch all the DSDT and SSDTx files in DSL format, and save to AML forma; or use the patched dir; or find the individual patches listed in the beginning of the all in one patches;
3. Install the kext files to OSX
4. Copy the EFI to EFI partition; Copy the DSDT and SSDTx AML files to APCI/patched/;
5. Set the UEFI boot in BIOS and disable safe boot (?or something named similar);

Everthing works except for Bluetooth. I switched my wireless card to ac7260, so won't try the original bluetooth anymore.

Use EFI in EFI_updated...backlight_works
L/E and S/L/E backup in working_sys...
Then apply the brightness key patch 

Note:

Put some useful documents in the docs, in case their server is down.

IASL sources settings, if not using the all in one patches:
![iasl parameters](https://raw.githubusercontent.com/GaryDoooo/acer_e51_osx/master/iasl_sources.png)

To fix the LED backlight, follow the video instruction in the fix backlight folder. The requied files are in the folder too.
