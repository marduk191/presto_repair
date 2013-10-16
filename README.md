presto_repair
=============

A windows script to install the proper bootchain files to the Pantech p9070 for AOSP based operation.


Usage:

git clone https://github.com/marduk191/presto_repair.git -b jellybean


This will include

- The proper bootchains from ICS
- The Gingerbread bootloader for full fastboot access
- TWRP 2.5
- Windows batch file for the bootchain install
- Slimbean 3.1.0 final for the p9070


Install:

After cloning the folder to your desktop

1. Run marfix.bat
2. Click install in recovery
3. Click Slim-3.1.0--20130831-0106-UNOFFICIAL.zip
4. Reboot When complete.

This bootchain is fine to use with all of the AOSP ROMs for the p9070.


Requirements:

A working adb driver from the Android SDK.






-marduk191
