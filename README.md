May.23,2020: 
# MAC OSX Catalina 15.4 installed on ASUS ROG Z390I Motherboard with OpenCore 0.5.8


# MAC OSX Catalina 15.2 installed on ASUS ROG Z390I Motherboard with OpenCore 0.5.4

## 1. Platform Part List

  CPU:	Intel  Core i7-9700K 3.6 GHz 8-Core Processor

  Motherboard:	Asus ROG STRIX Z390I ITX LGA1151 Motherboard

  Memory:	DDR4 32GB (2x16GB) 3200MHz Memory

  Video Card:	Yeston  Radeon RX 560D 4 GB Video Card (1 DP, 1 HDMI)

  SSD1:  Samsung 970 PRO 512GB M.2 NVMe SSD (For MacOS Catalina)

  SSD2:  Intel 760P 512GB M.2 NVMe SSD (For Windows10)

## 2. USB stick for install

  (1) On a MAC, using DiskUtility GUI tool to create a 16GB+ USB stick named Catalina with GUID partition and Apple JHFS+ file system

  (2)Create a MacOS USB installer

  sudo /Applications/Install\ macOS\ Catalina.app/Contents/Resources/createinstallmedia --volume  /Volumes/Catalina --applicationpath /Applications/Install\ macOS\ Catalina.app --nointeraction

  (3)Install OpenCoer 0.5.4 or above to the EFI partition on USB stick

  (4)Boot from the USB stick and install MacOS Catalina (using UEFI boot only)

## 3. Working

  Catalina 15.1 install and boots successfully, and than updated to 15.2, 15.3 (with OpenCore 0.5.6)

  Yeston RX 560D DP output linked to an AOC 27" 4K display

  Wired Ethernet - Intel I219V7 PCI Express Gigabit Ethernet

  USB ports

  Sleep/Wake

  Audio (ALC1220) with DP 

  On board Bluetooth

## 4. Not Working

  WIFI (Intel 9560 on ASUS ROG STRIX Z390I Motherboard)
