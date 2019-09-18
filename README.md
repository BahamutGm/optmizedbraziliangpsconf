# Brazilian Optimized GPS File Replacer
If you note live in Brazil, please don't install the module.
This module provides an improved GPS functionality with a better and faster accuracy location reference.

## How it works?
   The stock Android **_gps.conf_** file found in `system/etc/gps.conf` or `system/vendor/etc/gps.conf` is replaced with a new one correctly edited for a better improvement and faster satellite signals fix/lock.  
   This file is responsible for the correct GPS operation and functionality.  
   The default file found in most ROMs is very wrong and has a lot of bad information and settings for the correct operation and functionality of the GPS and A-GPS.  
   
## Requirements
- A device with Qualcomm Snapdragon chipset based.
- Rooted with Magisk and Magisk Manager indeed installed.

*__Note:__ Tested on the Redmi Note 7 Pro running MIUI by xiaomi.eu 10.3.11 Stable (PFHCNXM) Android Pie*

## Instructions
__It's Magisk install-able, don't install it by TWRP but with Magisk instead!__

#### Option 1 - Manually
1. Go to Magisk Manager **_Modules_** section.
2. Click on **_+_** yellow button and search/find for this **_"optimizedbraziliangpsconf.zip"_** file and long press on it.
3. Select open and after installed then reboot your device.
4. After rebooted your device, make sure your location settings is setup on mode **_Device only_**.
5. Skirt outdoors, can be in the yard of your house or anywhere else with a line of sight to the sky and stay in that outdoor place.
6. Download some Compass app on Google Play Store *(I recommend the **Compass Steel 3D**)* and then calibrate the compass.
7. Download **_GPS Locker_** app on Google Play Store and open the app and wait for the first time fix/lock. *This is necessary and essential because the app will recognize some GPS satellites signals for the very first time.*

#### Option 2 - Download
1. Go to Magisk Manager **_Downloads_** section.
2. Search/Find **_"Brazilian Optimized GPS File Replacer"_**.
3. Tap on the download button and then on **_INSTALL_**.
4. Wait a moment to finish downloading and installing.
5. When finished tap on **_REBOOT_**.
6. Same **_4, 5, 6 and 7_** steps of **_Option 1 - Manually_**.

## Notes
1. Location mode __"Battery saving"__ is removed in Android 9/Pie and above due to location service changes. To avoid Google location tracing, turn off __"Google Location Accuracy"__ in location settings (this still may provide some data to Google through the GPS supplement system).*
2. Consider using the __GPS Locker__ app because it is much better than the __GPS Test__ and __GPS Data__. You just need to open it once and wait for fix, then your gps signal is locked and when you close it (just press __Cancel__ in __"Unlock GPS on exit"__ message) the app keep awake running in the background.
3. GPS is made to work in outdoor places. For indoor/enclosed places such as inside of your house don't forget that, it will take a bit more to fix. It drains more battery, but is required if you're an advanced user that uses gps all the time.*  
   
## Changelog
#### Version 1.0
- Initial release

#### Version 2.0
- Last update and final version
- Fix for Oreo devices where the gps.conf was in /vendor

#### Version 2.1
- Template 1500 -> 17000

#### Version 3
- Enable MSA
- New Magisk module format

#### Version 4
- Huge clean-up
- All configurations explained
- Enable C2K for faster locking
- Support features on newer devices
- Use RHEL's ntp.org time pool

## Links
- [GitHub Module Page](https://github.com/Magisk-Modules-Repo/optmizedgpsconf)
