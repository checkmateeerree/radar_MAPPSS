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

### 6 

Run the arduino program, and it should work!
