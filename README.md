# How to get radar to work

### 1

Install Infineon Toolbox at https://www.infineon.com/cms/en/tools/landing/infineontoolbox.html

### 2

Open up infineon toolbox, and search+download in the manage Tools section:

1. Sense2GoL Pulse
2. XMCFlasher
3. Radar Gui

### 3 

Download the latest version of https://www.segger.com/downloads/jlink/#J-LinkSoftwareAndDocumentationPack. These are USB drivers that ensure that the Sense2GoL Pulse will properly connect to your computer through a USB cable.

### 4

Connect to the Radar/Arduino with a USB cable (into the debug port)

### 5 

1. Insert a micro USB cable (Debug) into the Baseboard
2. Open Infineon Toolbox → XMCTM Flasher
3. Check that Debugger Type is "SEGGER", otherwise go to: "Configurations" → "Setup", then set it to "SEGGER"
4. Click on "Connect" → XMC4700-2048

## Now you are done with the hardware setup, let's move on to the arduino set up

### 1

Open Arduino, and at the top left corner, you see "File". Click that, then click "Preferences".

### 2 

Once in preferences, navigate to "Additional Boards Manager URLs" (it's near the bottom), and enter this link: https://github.com/Infineon/Assets/releases/download/current/package_infineon_index.json. Click OK.

### 3

Then, on the top left of Arduino, navigate to Tools, Board:, and Manage Boards. On the Boards manager, search up: **XMC Microcontroller**, and install the "Infineon's XMC Microcontroller" package.


### 6 

Run the arduino program, and it should work!

**Click this link to gain a deeper understanding of the radar module: https://www.infineon.com/dgdl/Infineon-S2GL_Application_Note_AN597-ApplicationNotes-v01_00-EN.pdf?fileId=5546d4626b2d8e69016b89403b9342aa**
