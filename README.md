# Dell-G7-7588-Monterey
Based on Dell G7 USA

This repository contains the Opencore EFI for Laptop Dell G7 7588 fully working with Monterey 12.6.5.

What Works:

Intel GPU UHD 630 - LVSD Monitor and DP port. (HDMI not yet...) with metal acceleration.
Audio internal and through DP port (DP audio only when lid is close).
Card Reader.
Bluetooth.
Airport Wifi with Airdrop support.
Ethernet based on Killer E2200
Completely USB Mapping USB2/USB3/USB-C Switch.
NVME bus fixed.
HiDPI fix for audio glitches and distortion through headphones port.

What doesn't work:
NVIDIA GTX 1060 max-Q design.

Special thanks to Juan Vásquez Castro https://github.com/Juan-VC for HiDPI patch and post command install script.

INSTALLATION:

Format your install media as HFS+ and copy this EFI folder in the EFI partition. I used Opencore 0.9.1 with last kexts version at now.
I hope this will be useful.

Thanks Andrea and Nico.

NOTE:
To install Audio Patch open terminal and write chmod +x <scriptfile.sh> and double click. 	
