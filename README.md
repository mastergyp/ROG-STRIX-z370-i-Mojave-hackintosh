# ASUS ROG STRIX Z370-i Gaming Hackintosh
# Hardware

name | spec 
---|---
MB | ASUS ASUS ROG STRIX Z370-i Gaming ITX 
CPU| i7 8700
Cooler|Noctua NH-L9i 
Case|InWin Chopin
Wifi|Replace to Apple BCM943602CS 
Memery| G.SKILL Sniper X 3200 8G*2
SSD | Samsung SM951 256GB

# WORKING
> Wi-Fi ( Onboard WiFi card was replaced, see components list above )  
> Bluetooth
> Ethernet Port
> Sound --> Intel HDMI/DP Audio and Realtek Audio S1220A / Fix front pannel micphone not work / Fix wake after sleep  S1220A audio error
> NVMe SM951 / Trim
> i7-8700 ( six-physical cores and 6 virtual - HT )
> Intel UHD630 (configured with DisplayPort attached to Asus board) 
> Sleep
> Power Management and P-States        
> USB 3.0
> USB 2.0
> HandOff
> AirDrop
> iMessages
> iCloud
> Hardware Acceleration
> AirPlay
> iBooks
> Personal Hotspot

# BIOS Settings
**Save & Exit → Load Optimized Defaults**
F2 to enter BIOS on Asus Z370 Strix 2 - Switch to Advanced Mode F7
Exit → Load Optimized Defaults : Yes
Advanced \ System Agent(SA) Configuration → Vt-d : Disabled
Advanced \ PCH Configuration → IOAPIC 24-119 Entries : Enabled
Advanced \ APM Configuration → Power On By PCI-E/PCI : Disabled
Advanced \ Network Stack Configuration → Network Stack : Disabled
Advanced \ USB Configuration → Legacy USB Support : Auto ( needs to be auto for SSDT-UIAC.aml to work )
Boot → Fast Boot : Disabled
Boot → Secure Boot → OS Type : Other OS
Boot → CSM : Disabled ( Only enable if using dual monitor setup)
Ai Tweaker → Asus MultiCore Enhancement: Disable ( but only if you have intel stock CPU cooler ! )
Integrated Graphics : Enabled
iGPU MultiMonitor : Enabled
DVMT Pre-Allocated : 128Mb 4. Primary Display : Auto

# Update Log

  ## 2018-10-07
 - Mojave 10.14.1

---


