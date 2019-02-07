# HP-Elitepad-900-WR81

## Outline of the problem:

I have an Elitepad 900 tablet from 2013. The device is still in great condition, but due to software reasons it is not suitable for work. Even when it was brand new, 32 GB of built-in memory did not allow much. In addition to system partitions, HP placed the recovery partition, which occupied over 3 GB of available space. After several updates, the available disk space no longer allowed anything.

Performance is also a big problem. Atom Z2760 processor and 2GB RAM do not allow too much. Working on an unoptimized Windows system, full of unnecessary processes and applications, is painful.

The first idea for the resurrection of my Elitepad was to install some light Linux. Unfortunately, this is a business device and UEFI does not allow you to boot anything except windows. To have more disk space and RAM at my disposal, I had to prepare my own version of Windows 8.1. Because the preparation of such a system requires many tests and minor changes, I have set up this repository for easier supervision of the project.

## about this branch:
after installing the master branch version, the rotation sensor does not work

#### changes (compared to master branch):

* Remove-Multimedia
  * Embadded Lockdown Manager (false)
* Tweaks
  * Desktop - Hide Icons (false)

* Services
    * Sensor Monitoring Service (Automatic)

#### result:
* these changes have not solved the problem
