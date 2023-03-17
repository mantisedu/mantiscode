# Introduction
This guide contains instructions for installing MantisCode, along with step by step guides that will enable you to control and connect with various sensors.

# Overview
Mantis Code is a cross platform application that allows for you to run Scratch programs and interact with various MantisEDU Sensors out of the box.

# Required Hardware
In order to use MantisCode, you will need to have access to a Bluegiga BLED112 Bluetooth dongle, manufactured by Silicon Labs, https://www.silabs.com/wireless/bluetooth/bluegiga-low-energy-legacy-modules/device.bled112?tab=specs.

# Software Installers
Below you'll find the necessary files to install on both Windows and MAC Operating Systems.

## Windows OS Installer
To download the windows installer, please visit this link, https://mantisedu.io/downloads/MantisCode-v3.3.0.95.msi
After downloading the MSI follow these steps to run the application.

1. Click the MSI file
2. If you are presented with the Windows protected your PC window", click more info, followed by Run Anyway to proceed.
3. MantisCode will now be available under programs.

## macOS Installer
To download the macOS installer, please visit this link, https://mantisedu.io/downloads/MantisCode-v3.3.0.95.dmg

 1. Click on the DMG file you downloaded 
 2. Drag MantisEDU icon into the applications folder
 3. Right click on the MantisEDU icon from the application folder and select "Show Package Contents"
 4. Right click and select Open a terminal from the MacOS folder
 5. Run this command "chmod -R 755 *" and press enter

*Please note that steps 1 through 5 only have to run once.  In the future, you can simply click on the MantisEDU App Icon from your applications folder.   
![This is an image](https://raw.githubusercontent.com/mantisedu/mantiscode/main/docs/images/permissions2.gif)

Figure 1: Installing DMG and applying permissions.

If the app does not load, follow the steps in macOS permissions to add an security exception.

### macOS Permissions
1.  In the Finder  on your Mac, locate the app you want to open. (Don’t use Launchpad to do this. Launchpad doesn’t allow you to access the shortcut menu.)
2.  Control-click the app icon, then choose Open from the shortcut menu.   
3.  Click Open.

The app is saved as an exception to your security settings, and you can open it in the future by double-clicking it just as you can any registered app.

If you have problems with this step, visit the Apple [website](https://support.apple.com/guide/mac-help/open-a-mac-app-from-an-unidentified-developer-mh40616/13.0/mac/13.0) and select your operating system from the dropdown for complete instructions.  

# Running Mantis Code
After completing these steps, MantisCode has been installed.  Makes sure your dongle is plugged into and open USB port, and open MantisCode from the location you chose during the install process.

There are a number of starter examples available from the home screen.  Follow the steps below to control the MotorHat.
Click on Mantis Sensors from the home screen.

![This is an image](https://raw.githubusercontent.com/mantisedu/mantiscode/main/docs/images/mantiscode.png)
Figure 2: Mantis Code Home Screen

Click on the Mantis Motor Hat button to access the Motor Hat projects.

![This is an image](https://raw.githubusercontent.com/mantisedu/mantiscode/main/docs/images/sensors.png)
Figure 3: Mantis Code Sensors

Click on Option 1, to load a sample program that will connect to the Motor Hat and display sensor values.

![This is an image](https://raw.githubusercontent.com/mantisedu/mantiscode/main/docs/images/robotstarter.png)
Figure 4: Mantis Motor Hat

Add power to your Motor Hat and then click on the green arrow and the program will connect to your Motor Hat.

![This is an image](https://raw.githubusercontent.com/mantisedu/mantiscode/main/docs/images/robotprogram.png)
Figure 5: Robot Starter Program

After the program successfully connects to the Motor Hat, the LED's will change from Green to Blue.  At this point, you can use the up, down, left and right arrows to control the robot. Figure 6 illustrates this process from end to end.

![This is an image](https://raw.githubusercontent.com/mantisedu/mantiscode/main/docs/images/end2end.gif)

Figure 6: End to End Process