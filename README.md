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
1. Follow the prompt and drag the DMG into the application folder.
2. Open the MantisCode app from the Applications Folder, or by using Finder.

If you receive an the Error "The Application "MantisEdu" Can't be opened as in Figure 1:, please follow the steps below under macOS Permissions.

![This is an image](https://raw.githubusercontent.com/mantisedu/mantiscode/main/docs/images/error.png)

Figure 1: Error Screen

### macOS Permissions

Open your finder app, and search for Security & Privacy.  By default, macOS does not allow apps to run from unknow publishers.   Figure 2 show the default settings.

![This is an image](https://raw.githubusercontent.com/mantisedu/mantiscode/main/docs/images/security1.png)

Figure 2: Default Security Settings
In order to allow the app to run do the following:

 1. Click the unlock button and type in your password.  
 2. Open a new terminal window
 3. Type the following command and press enter "sudo spctl --master-disable"
 4. Exit and return back to Security & Settings
 5. Select the Anywhere option 

![This is an image](https://raw.githubusercontent.com/mantisedu/mantiscode/main/docs/images/EnableApps.gif)

Figure 3: Enable App Workflow

After completing this step, Figure 4 illustrates the approprate configuration.

![This is an image](https://raw.githubusercontent.com/mantisedu/mantiscode/main/docs/images/security2.png)
Figure 4: Valid Configuration to Allow Apps

Now that apps are allowed, you can install the app.

 1. Click on the DMG file you downloaded 
 2. Drag MantisEDU icon into the applicaitons folder
 3. Right click on the MantisEDU icon from the applicaiton folder and select "Show Package Contents"
 4. Right click and select Open a terminal from the MacOS folder
 5. Run this command "chmod -R 755 jre1.8.0_172" and press enter
 6. Run this command "sh MantisScratchConnector.sh" to launch the program

*Please note that steps 1 through 5 only have to run once.  In the future, you can simiply open the terminal from the MacOS folder and run "sh MantisScratchConnector.sh" to open the program.

![This is an image](https://raw.githubusercontent.com/mantisedu/mantiscode/main/docs/images/permissions.gif)

Figure 5: Open App from Terminal

For more detailed instructions on how to add an app exception, please visit the Apple [website](https://support.apple.com/guide/mac-help/open-a-mac-app-from-an-unidentified-developer-mh40616/13.0/mac/13.0) and select your operating system from the dropdown.  Following these steps will allow for you to be able to run MantisCode from the desktop icon, vs having to type the terminal commands. 

# Running Mantis Code
After completing these steps, MantisCode has been installed.  Makes sure your dongle is plugged into and open USB port, and open MantisCode from the location you chose during the install process.

There are a number of starter examples available from the home screen.  Follow the steps below to control the MotorHat.
Click on Mantis Sensors from the home screen.

![This is an image](https://raw.githubusercontent.com/mantisedu/mantiscode/main/docs/images/mantiscode.png)
Figure 6: Mantis Code Home Screen

Click on the Mantis Motor Hat button to access the Motor Hat projects.

![This is an image](https://raw.githubusercontent.com/mantisedu/mantiscode/main/docs/images/sensors.png)
Figure 7: Mantis Code Sensors

Click on Option 1, to load a sample program that will connect to the Motor Hat and display sensor values.

![This is an image](https://raw.githubusercontent.com/mantisedu/mantiscode/main/docs/images/robotstarter.png)
Figure 8: Mantis Motor Hat

Add power to your Motor Hat and then click on the green arrow and the program will connect to your Motor Hat.

![This is an image](https://raw.githubusercontent.com/mantisedu/mantiscode/main/docs/images/robotprogram.png)
Figure 9: Robot Starter Program

After the program successfully connects to the Motor Hat, the LED's will change from Green to Blue.  At this point, you can use the up, down, left and right arrows to control the robot. Figure 10 illustrates this process from end to end.

![This is an image](https://raw.githubusercontent.com/mantisedu/mantiscode/main/docs/images/end2end.gif)

Figure 10: End to End Process