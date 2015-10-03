# ADB-Google-Glass
Mac Only.  Should work on all Android devices and versions which use ADB.

Specifically Designed for Google Glass running KitKat 4.4 or XE22.


Automated installation and uninstallation of .apk to Google Glass using ADB.  Automates the terminal registration process for Android Debug Bridge.  Then prompts to install or uninstall apk.

The purpose of this build is to streamline the registration of USB and WiFi connected Android devices to the Android Debug Bridge (ADB). It is designed to be an all in one, lightweight, ready to use setup to quickly register and allow commandline input for ADB through the terminal application.  It also automates the installation and uninstallation process of .apks.

How to use:

Make sure the android device has WiFi enabled and is connected to the same WiFi network as the mac being used.  It will be necessary to trust the connected Mac the first time this process is run, at some point the device will ask to trust the computer.  Tap --Trust--.

Connect the Android device to Mac with a USB cable.  Run the application ADB-Google-Glass.app.  A terminal window will open displaying the connected Adroid devices.  A dialog box will open asking to install or uninstall

Install:
Select the .apk to install and select Choose.  Watch for a response in the open terminal window for success or failure.

Uninstall:
Filter the type of .apk by system, third-party or all.  The terminal window will begin running process to determine the names of installed .apk packages.  Once the process is complete a list of installed application will be displayed in the terminal window.  Select the package you wish to uninstall (the name should look something like this com.company.glass.app) and click uninstall.    Watch for a response in the terminal window for success or failure.

This application uses applescript to run the terminal processes necessary to register an Android device to ADB.  The ADB Platform-tools files from the most recent version of SDK are included in the application. There is no need to download SDK to use ADB.

To see the applications contents right click on the app icon and select Show Package Contents.

