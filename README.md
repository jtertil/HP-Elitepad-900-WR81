# HP-Elitepad-900-WR81

## Outline of the problem:

I have an Elitepad 900 tablet from 2013. The device is still in great condition, but due to software reasons it is not suitable for work. Even when it was brand new, 32 GB of built-in memory did not allow much. In addition to system partitions, HP placed the recovery partition, which occupied over 3 GB of available space. After several updates, the available disk space no longer allowed anything.

Performance is also a big problem. Atom Z2760 processor and 2GB RAM do not allow too much. Working on an unoptimized Windows system, full of unnecessary processes and applications, is painful.

The first idea for the resurrection of my Elitepad was to install some light Linux. Unfortunately, this is a business device and UEFI does not allow you to boot anything except windows. To have more disk space and RAM at my disposal, I had to prepare my own version of Windows 8.1. Because the preparation of such a system requires many tests and minor changes, I have set up this repository for easier supervision of the project.

## about this branch:

* Removed accessories:
  * Accessibility 
  * Anytime Upgrade 
  * Application Experience (Compatibility Tab) 
  * Auto Play 
  * Automatic Maintenance 
  * Briefcase 
  * Character Map 
  * Diagnostics Troubleshooting Wizard 
  * Disk Quota 
  * Display Color Calibration 
  * ELS (Extended Linguistic Services) 
  * Help and Support 
  * Imapi 
  * Input Method Editor 
  * Natural Languages 
  * Notepad 
  * Paint 
  * Previous Versions 
  * Private Character Editor 
  * Recovery Drive Creator 
  * Screen Magnifier 
  * Screen Reader 
  * Sound Recorder 
  * Spell Checking 
  * Steps Recorder 
  * Sticky Notes 
  * System Restore 
  * Tablet PC (Flick Learning Wizard) 
  * Tablet PC (Journal) 
  * Tablet PC (Keyboard Input Panel) 
  * Tablet PC (Text Prediction) 
  * Welcome Center 
  * Windows Contacts 
  * Windows Easy Transfer 
  * Windows Mail 
  * Windows Mail (Send to Desktop shortcut) 
  * Windows Recovery Environment 
  * Windows Sidebar 
  * Wordpad 
  * Write 
  * Zip 
  
* OS + Drivers takes 7,96 GB, ISO file: 2,05 GB.
* Clean system after restart need 520 MB of RAM.

## after installation:

1. SP71504 ElitePad 900 BIOS/Firmware/Driver Update
  * I must force reset after installation
2. SP65877 Atheros AR600x 802.11abgn Wireless LAN Driver
3. SP65376 AR3002
4. SP64759 REALTEK CARD READER
5. SP64682 GPS
6. SP64673 NFC
