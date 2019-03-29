## iDroider - iOS and Android CFW
* Supports iPhone 2g, 3g, and iPod Touch 1g
* Custom Firmware Bundled with iOS 3.1.2 and Android 2.2.3
* Uses iDroider Desktop Program to install OpeniBoot, making this a “2 step” install
* No special version of iTunes is needed for this tool

## The Custom Firmware
iDroider Comes Preloaded with:
* iOS 3.1.2
* Android (iDroid) 2.2.3
* OpenSSH
* MobileTerminal
* iFile
* iDroiderTools3
* iDroiderDrivers
* Bundle of additional cmd tools
* Updated dpkg
* Fixed Cydia for iOS 3 (Soon)
* Full Jailbreak (Using Pwnage)

## How to install

macOS
* Download the IPSW for your device from [here](link)
* Download iDroider Desktop Program from [here](link)
* Drag the iDroider Program to /Applications 
* Plug in device in dfu mode press “Enter Pwned DFU” on iDroider Desktop Program
* iTunes will open, simple Alt-Click Restore and select the IPSW you downloaded
* Let it restore once on the homescreen turn of the device
* Turn it back on and let it sit for 5-7 minutes (This is extremely important as it needs to copy all files)
* Once done feel free to confirm it worked by opening iFile and looking in /var and see if there are 5 new files
* Put device into recovery mode and open iDroider Program 
* Press “Install OIB for (Your Device)” you should see your screen turn white and open a screen with 4 options, use the volume up to select “install” hit the home button 
* Let it install this could up to 15 mins, if you have issues let me know.
* Once install or if you only want to just boot android, select the iDroid and press the home button
* iDroid will boot and you see the android homescreen, Enjoy!

Windows
* Download the IPSW for your device from [here](link)
* Download iDroider Bat File from [here](link)
* Plug in device in dfu mode 
* Run idroider.bat and select “4”
* iTunes will open, simple Shift-Click Restore and select the IPSW you downloaded
* Let it restore once on the homescreen turn of the device
* Turn it back on and let it sit for 5-7 minutes (This is extremely important as it needs to copy all files)
* Once done feel free to confirm it worked by opening iFile and looking in /var and see if there are 5 new files
* Put device into recovery mode and open iDroider Bat File
* Select  “1, 2, or 3” (Depends on device) you should see your screen turn white and open a screen with 4 options, use the volume up to select “install” hit the home button 
* Let it install this could up to 15 mins, if you have issues let me know.
* Once install or if you only want to just boot android, select the iDroid and press the home button
* iDroid will boot and you see the android homescreen, Enjoy!


Linux
* Download the IPSW for your device from [here](link)
* Download iDroider.sh File from [here](link)
* Plug in device in dfu mode 
* Run idroider.sh and select “4”
* Restore Using your method of choice such as; idevicerestore, VM, Wine iTunes, etc
* Once restore is done and you are on the homescreen shutdown the device
* Turn it back on and let it sit for 5-7 minutes (This is extremely important as it needs to copy all files)
* Once done feel free to confirm it worked by opening iFile and looking in /var and see if there are 5 new files
* Put device into recovery mode and open iDroider.sh File
* Select  “1, 2, or 3” (Depends on device) you should see your screen turn white and open a screen with 4 options, use the volume up to select “install” hit the home button 
* Let it install this could up to 15 mins, if you have issues let me know.
* Once install or if you only want to just boot android, select the iDroid and press the home button
* iDroid will boot and you see the android homescreen, Enjoy!

#FAQ
* Can this be done on Linux - Yes but you will have to compile yourself and find a way to restore
* Does it work on all macOS and Windows versions - Yes aslong as your have a newer iTunes 

## Coming soon!

* Clean up the code and make it run "better"
* Include OpeniBoot installer App on the phone/CFW for eaiser install
* Fixed SSL Errors in Cydia


* "heres the big one" Support for more Devices! (3gs, 4/4s, 5, 5c) **Not ios 7 on a 3gs or ios 11 on a 5/5c but dual booting and other CFW. Write up soon :P

* Untethered Dual-Boot with ios 6 and 7 for the iPod Touch 4g

* More Later!


## Disclaimer

**This is BETA software.**

Backup your data.

This tool is currently in beta and could potentially brick your device. It will attempt to save a copy of data in NOR to nor-backups folder before flashing new data to NOR, and it will attempt to not overwrite critical data in NOR which your device requires to function. If something goes wrong, hopefully you will be able to restore to latest IPSW in iTunes and bring your device back to life, or use nor-backups to restore NOR to the original state, but I cannot provide any guarantees.

**There is NO warranty provided.**

THERE IS NO WARRANTY FOR THE PROGRAM, TO THE EXTENT PERMITTED BY APPLICABLE LAW. THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE PROGRAM IS WITH YOU. SHOULD THE PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF ALL NECESSARY SERVICING, REPAIR OR CORRECTION.

**WARNING!**

* We are not help responsible for anything that happens to your device.
* It is possible that this will not work on your device.
* This could leave your device in a bootloop.
* Android on the iPhone 2g/3g and iPod Touch 1g is some what unstable.
* There will be crashing and issues.
* All data on the decvice will be deleted.

## Credit

* @tie1r for iDroider CFW, iDroider Program, idroidertools3, idroiderdrivers
* geohot for limera1n exploit
* posixninja and pod2g for SHAtter exploit
* iPhone Dev Team for 24Kpwn exploit
* pod2g for steaks4uce exploit
* iPhone dev team for Pwnagetool 
* iPhone dev team for Pwnage
* iPhone dev team for Pwnage 2.0
* iPhone dev team for Pwnage
* iDroid Project for OpeniBoot
* iDroid Project for iDroid Images
* iDroid Project for OpeniBoot
* iDroid Project for OiBC and loadibec

## Credit for iDroid Creators
<ul>
  <li><a href="https://github.com/bluerise">Patrick Wildt</a></li>
  <li><a href="https://github.com/boxingcow">boxingcow</a></li>
  <li><a href="https://github.com/CPICH">CPICH</a></li>
  <li><a href="https://github.com/ddominator">Rex Justin Lim</a></li>
  <li><a href="https://github.com/Neonkoala">Nick Dawson</a></li>
  <li><a href="https://github.com/nickpack">Nick Pack</a></li>
  <li><a href="https://github.com/oranav">Oran Avraham</a></li>
  <li><a href="https://github.com/ricky26">Ricky Taylor</a></li>
  <li><a href="https://github.com/planetbeing">David Wang</a></li>
</ul>

<p><b>Licensing for the original iDroid, OpeniBoot and the text written be myself on this page</b><p>
  <ul>
  <li>The original iDroid Wiki Text was under <a href="http://www.gnu.org/copyleft/fdl.html">GNU Free Documentation License 1.3</a></li>
  <li>Anything else from the original iDroid project was under <a href="https://creativecommons.org/licenses/by-sa/1.0/">CC BY-SA</a></li>
  <li>The text on this Git is written by myself and not copied from the original iDroid, but it is still under the same license as the original Wiki text (<a href="http://www.gnu.org/copyleft/fdl.html">GNU Free Documentation License 1.3</a>)</li>
</ul>

<p><b>This project comes with no warranties. You're responsible for your broken devices if you screw up. No support should be requested or will be given.</b><p>




