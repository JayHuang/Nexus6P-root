# **Setup:**

• On your phone, navigate to System>About Phone> Scroll to the bottom and tap on Build Number 7 times to enable Developer Options

• Navigate to Developer Options>OEM Unlocking, tap to Unlock OEM and confirm/follow the promp to enable OEM Unlocking

OEM Unlocking has now been enabled!!

===============================================================================

• Navigate to your device, Press and hold both Power and Volume buttons simultaneously for ~5 seconds

• You should appear at a new screen with the Androd mascot appearing and lines of code at the bottom of it, you have no gain accessed to Bootloader Mode

• Connect your phone to your PC through USB cable

• On your PC, install adb-setup-1.4.3.exe

• Follow the prompt

• Once installed, close it and go to CMD

• Once you have access to CMD, type fastboot

• Type fastboot devices

• switch your directory to your nexus root master folder location, Example: User>cd desktop>desktop>cd nexus6-root-master>nexus6-root-master>

================================================================================

• navigate to your device and set it up as if new. Make sure everything has been wiped and you are able to use it normally.

• Once you have set up your device, navigate to Settings and enable Developer Options again.

•  After enabling Developer options, re-connect your device to your PC. Make sure your device recognizes that it's connected to your PC.

• Access your command line in your pc and type adb devices

• A prompt should pop up on your device screen, press OK to authorize USB Debugging

• go to command line and type adb devices

• A prompt should appear, press OK and authorize USB Debugging 

• Return to CMD and ype adb reboot bootloader to access the bootloader on phone

• type on cmd fastboot flash recovery twrp-3.1.1-0-angler.img

• click install

• A file explorer should automatically open on your PC, if not, then proceed to the file explorer and find your connected device Download folder


• Copy and paste magiskmanager.apk and magisk.zip to the download folder

• Now on your device, navigate to the .zip folder in your download file 

• Install the .zip file

• Reboot your device once you installed

• Confirm to install twrp app

• Wait for your device to reboot

• once your device  is rebooted

• Navigate to your downloads folder and click on the .apk file and install

• Navigate to the magisk app

• Check that there are three greeen checkmarks

• Cow reconnect your usb cable to make sure that its connected to your pc

• Proceed to cmd and type adb reboot bootloader

• If you access the twrp screen, YOU DID IT! 

• Enter your current pattern 

• Go to reboot 

• Click on system

***YOU'RE DONE!!***
