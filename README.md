# Asus ROG Strix G15 - G512LV - OpenCore EFI
 
 Tested on macOS Big Sur
 
 NOTE:
 - Add your SMBIOS details and mac address in config.plist.
 - The AirportItlwm.kext is for Big Sur only, <a href="https://github.com/OpenIntelWireless/itlwm/releases">use the Catalina version if you are not on Big Sur.</a>
 - <a href="https://github.com/xzhih/one-key-hidpi">For Enabling macOS HiDPI.</a>
 
 OpenCore 0.6.5
 
 Specs:
 - Intel® Core™ i7 10750H Processor, 2.6 GHz
 - NVIDIA® GeForce® RTX 2060 (DISABLED)
 - 16G RAM
 - AX201 Wi-Fi 6 (802.11 ax (2x2))
 - ELAN1203 Touchpad
 
 What works:
 - Wifi
 - Bluetooth
 - Eathernet
 - iMessages
 - Trackpad (Thanks to <a href="https://github.com/ClefairyBlame">ClefairyBlame</a>)
 - 144hz display
 - Handoff
 - etc
 
 Whats does NOT work:
 - Airdrop (due to bluetooth limited support)
 - HDMI
 - USB-C DisplayPort output
 
 Credits:
 - Thanks to <a href="https://github.com/dkoluris">Dennis Koluris</a> for power managment fix.
