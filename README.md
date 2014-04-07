Samsung Galaxy Core (GT-I8262) device source / configuration for building Android 4.4.2 (Cyanogenmod 11.0)

Getting Started
-----------------------

To get started with CyanogenMod, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the CyanogenMod trees, use a command like this:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-11.0

Then to sync up:

    repo sync

Build your device:

    source build/envsetup.sh
    brunch arubaslim

Flash ZIP:

    out/target/product/arubaslim/cm-VERSION-DEVICENAME.zip


Please see the [CyanogenMod Wiki](http://wiki.cyanogenmod.org/) for building instructions.

For more information on this Github Organization and how it is structured,
please [read the wiki article](http://wiki.cyanogenmod.org/index.php/Github_Organization)

Disclaimer
--------

All of these device are not supported by CyanogenMod , and hence cut off by the CyanogenMod team. and this project is not endorsed or supported by the CyanogenMod team.


