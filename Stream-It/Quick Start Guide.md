![RIS header](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/RIS%20header.PNG)

# Powered by Bug Labs, Inc. 
## Using the Renesas Stream-It! Kit 

**Table of Contents** 
- [Getting Started](#getting-started)
- [Create Your Custom Dashboard](#create-your-custom-dashboard)
- [Using the Freeboard Dashboard](#using-the-freeboard-dashboard)
- [Do More](#do-more)

- [Helpful Links](#helpful-links)

## Getting Started

### Step 1

Open kit, follow the instructions in [The Renesas Stream-It! Quick Start Guide](https://github.com/buglabs/Renesas-RZ-Solution-Kits/raw/master/Stream-It/Files/Stream-It%20HW%20QGS.pdf)

### Step 2

Make sure you installed everything in the quick start guide, THEN 

#### Download the Binary

[Download the Binary from here](https://github.com/buglabs/Renesas-RZ-Solution-Kits/tree/master/Stream-It/Files/Firmware)

#### Run the Software

Use the [Stream it! - RZ Boot Loader](https://www.renesas.com/en-eu/software/D6001157.html) to run the application. It may be necessary to obtain this
loader application to use this method. 

Copy the ‘[StreamIt2_Dweet.bin](https://github.com/buglabs/Renesas-RZ-Solution-Kits/blob/master/Stream-It/Files/Firmware/StreamIt2_Dweet.bin)’ file into ‘StreamIt2_QSPI_Loader\scripts’ and rename the bin file to ‘StreamIt2_User_App.bin’. 

###### Run the batch file

‘Program_QSPI_Loader_Application.bat’ that is in the project ‘scripts’ folder.

A window should pop up for the few seconds that it takes for the binary file to be copied to the flash memory on
the Stream it! - RZ board.

Once the SPI flash has been reprogrammed the new code will be executed on device reset. 

This application will now run automatically each time the board is powered on.

### Step 3 

#### View your Device

Find your Thing-Name

https://renesas.dweet.io/follow/stream_test

[View your device in the Stream-It Default Dashboard.](https://renesas.freeboard.io/board/rVbZ2R)

## Create Your Custom Dashboard

### Step 1 

Navigate to https://renesas.dweet.io

### Step 2 

Enter your Stream-It "Thing Name".

[Where do I find my Thing Name"?](#view-your-device)

![RIS entry](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/RIS%20entry.PNG)

### Step 3

Click "Try it now!"

Congratulations! You can now monitor your device in real-time with a custom dashboard, like below:

![stream-it dash](https://github.com/buglabs/Renesas-RZ-Solution-Kits/raw/master/Stream-It/Files/Pictures/stream-it%20dash.PNG)

## Using the freeboard Dashboard

The Stream-It kit and dashboard communicate using dweet. [Learn more about dweet](https://dweetPro.io)

Depress the button on the Stream-It kit to see the indicator light on the dashboard turn on.

Click on one of the LED Indicators to turn the corresponding LED on or off on the Stream-It kit.

### More about Using freeboard

[Freeboard](https://freeboard.io) is a web-based visualization tool used for displaying and interacting with data. [Freeboard](https://freeboard.io) is open-source and fully-customizable, allowing the user to create rich Internet of Things applications.

[Customize your dashboard](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/README.md#using-freeboard)

[Sign up for a Renesas Freeboard account to do more](https://renesas.freeboard.io/signup)


## Do More

[Customize your dashboard](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/README.md#using-freeboard)

[View the Data Monitoring API documentation](https://renesas.dweet.io/play/)

[Learn more about the Renesas IoT Sandbox and download documentation and source code for the kit](https://www.renesas.com/iotsandbox)

[Try the S5D9 Cold Chain Demo](https://github.com/buglabs/Synergy-Starter-Kit/blob/master/Cold%20Chain/User%20Guide.md) 


## Helpful Links

[Support for the Renesas Stream-It! kits](https://www.renesas.com/en-us/solutions/key-technology/human-interface/rz-stream-it-v1.html)

[Freeboard Open Source Repo](https://github.com/Freeboard/freeboard)

[DweetPro Production ready APIs and UI](https://dweetpro.io)

[Data Monitoring developer area](https://renesas.dweet.io/) 


## Notes


![BUG logo gif](https://github.com/buglabs/Synergy-Starter-Kit/raw/master/Pictures/BUG_logo_gif.gif)
