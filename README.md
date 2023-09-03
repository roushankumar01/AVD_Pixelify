# AVD_Pixelify

### Creating AVD by Android Studio
* Device : Pixel 6
* SDK 29 (Google API)
* Arc : x86
* Allocate RAM and Storage according to your use
Start AVD

### Root AVD by rootAVD (https://github.com/newbit1/rootAVD)
#### Preconditions
* the AVD is running
* a working Internet connection for the Menu
* a command prompt / terminal is opened
* `adb shell` will connect to the running AVD

A Script to...
* root your Android Studio Virtual Device (AVD), with Magisk (Stable, Canary or Alpha)
* patch its fstab
* download and install the USB HOST Permissions Module for Magisk
* install custom build Kernel and its Modules
* download and install AOSP prebuilt Kernel and its Modules

...within seconds.

###Install Pixelify Module (https://github.com/Kingsman44/Pixelify)
*Download latest Pixelify Module ZIP and Copy it to AVD
*Install Module by Magisk and restart

### Remove Preinstalled Google Photos by De-Bloater (https://github.com/sunilpaulmathew/De-Bloater) then install latest version of Google Photos APK
*Install De-Bloater APK Grant Root access then delete Photos App and restart AVD
*Download latest APK of Google Photos for X86 or according to your AVD arc
*Install APK
*Login to you Google Account and enjoy unlimited photos and videos to Google Photos in Original quality
