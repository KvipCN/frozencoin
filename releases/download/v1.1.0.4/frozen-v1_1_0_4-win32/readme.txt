
===============
Frozen v1.1.0.4
===============

This is Version 1.1.0.4 of Frozen for Windows (32bit). It contains:

- frozen-qt.exe - The GUI version of Frozen - the standard wallet for Windows
- frozend.exe   - The frozen daemon. Use it if you want to run Frozen without graphical interface
- frozen.conf   - A sample Frozen configuration file
- md5sum.txt    - The MD5-sum of each of the binaries above
- readme.txt    - This text
- Makefile      - Helps to generate md5sum.txt


LOCATION OF frozen.conf
-----------------------

The location of a custom frozen.conf depends on your version of Windows:

    Windows 7       C:\Users\<username>\AppData\Roaming\Frozen\frozen.conf                          
    Windows Vista   C:\Users\<username>\AppData\Roaming\Frozen\frozen.conf                          
    Windows XP      C:\Documents and Settings\<username>\Application Data\Frozen\frozen.conf

PLEASE NOTE: the name of the directories "AppData" or "Application Data" will be localized
to your Windows langauge. The directories will usually be hidden. In order to access them
you may need to check "show hidden files and folders" in the folder options.


BUILD information
-----------------

The executables are build basically according to the process to build the Bitcoin-binaries
described by the user nitrogenetics in: https://bitcointalk.org/index.php?topic=149479.0 

Toolchain:
    - mingw
    - ActivePerl-5.18.1.1800-MSWin32-x86-64int-297570.msi
    - python-3.3.2.msi
    - gcc x32-4.8.1-release-posix-dwarf-rev5.7z

Libraries:
    - boost_1_54_0
    - db-4.8.30.NC
    - miniupnpc-1.8
    - openssl-1.0.1e
    - qt-everywhere-opensource-src-5.1.1

