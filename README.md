# HP-Elitepad-900-WR81

## Outline of the problem:

I have an Elitepad 900 tablet from 2013. The device is still in great condition, but due to software reasons it is not suitable for work. Even when it was brand new, 32 GB of built-in memory did not allow much. In addition to system partitions, HP placed the recovery partition, which occupied over 3 GB of available space. After several updates, the available disk space no longer allowed anything.

Performance is also a big problem. Atom Z2760 processor and 2GB RAM do not allow too much. Working on an unoptimized Windows system, full of unnecessary processes and applications, is painful.

The first idea for the resurrection of my Elitepad was to install some light Linux. Unfortunately, this is a business device and UEFI does not allow you to boot anything except windows. To have more disk space and RAM at my disposal, I had to prepare my own version of Windows 8.1. Because the preparation of such a system requires many tests and minor changes, I have set up this repository for easier supervision of the project.

## about this branch:

* OS + Drivers takes 8,45  GB, ISO file: 2,31 GB.
* Clean system after restart need 390 MB of RAM.

* features:
  * AD LDS Services: removed
  * Direct Play: enabled
  * Hyper-V: removed
  * Internet Explorer 11: removed
  * Internet Information Services (IIS): removed
  * Microsoft Message Queuing (MSMQ): removed
  * Net Framework 3.5: enabled
  * Net Framework 4.5 Network Advanced Services: enabled
  * Printing - LPR Port Monitor: removed
  * Printing - LPD Print Service: removed
  * Printing - Internet Printing: removed
  * Printing - Fax and Scan Services: removed
  * Remote Access Connection: removed
  * Remote Differential Compression API: removed
  * Simple Network Management Protocol (SNMP): removed
  * Simple TCP: removed
  * SMB1 Protocol: removed
  * Tagged Image File Format IFilter (TIFF iFilter): removed
  * Telnet Client and Server: removed
  * Trivial File Transfer Protocol (TFTP): removed
  * Windows Defender: removed
  * Windows Identity Foundation 3.5: enabled
  * Windows Media Player: removed
  * Windows Mobile PC: enabled
  * Windows PowerShell: enabled
  * Windows Search: enabled
  * Work Folders: removed
  * XPS Viewer and Printer: removed
