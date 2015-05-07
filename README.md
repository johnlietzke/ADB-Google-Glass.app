# ADB-Google-Glass
Mac Only.  For Android devices running KitKat 4.4 or XE22.

Automated installation and uninstallation of .apk to Google Glass using ADB.  Automates the terminal registration process for Android Debug Bridge.  Then prompts to install or uninstall apk.

The purpose of this build is to streamline the registration of USB and WiFi connected Android devices to the Android Debug Bridge --> (ADB). It is designed to be an all in one, lightweight, ready to use setup to quickly register and allow commandline input for ADB through the terminal application.  More efficently allows installation and uninstallation of .apk to Google Glass using ADB.

How to use:

Make sure the android device has WiFi enabled and is connected to the same WiFi network as the mac being used.  It will be necessary to trust the connected Mac during the first time this process is run, at some point the device will ask to trust the computer.  Select --Trust--.

Connect the Android device to Mac with a USB cable or WiFi (see ADB-Wireless.app).  Run the application ADB-Google-Glass.app.  A terminal window will open displaying the connected Adroid devices.  A dialog box will open asking to install or uninstall

Install:
Select the .apk to install and select Choose.  Watch for a response in the open terminal window for success or failure.

Uninstall:
The terminal window will begin running process to determine the name of installed third party .apk packages.  Once the process is complete a list of installed application will be displayed in the terminal window.  Find the package you wish to uninstall (the name should look something like this com.company.glass.app).  Copy the name from the terminal window and paste it into the dialog box promt and select ok.  Watch for a response in the terminal window for success or failure.

This application uses applescript to run the terminal processes necessary to register an Android device to ADB.  The ADB files from the most recent version of SDK are included in the application. There is no need to download SDK to use ADB.

To see the applications contents right click on the app icon and select Show Package Contents.

