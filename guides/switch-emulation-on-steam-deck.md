# Switch Emulation on Steam Deck

Watch the video here: [Steam Deck Emulation - EVERY New Switch Exclusive Tested](https://youtu.be/A09_2yy5f2o)
[![Fan the Deck Switch Emulation on Steam Deck Video](https://i9.ytimg.com/vi/A09_2yy5f2o/maxresdefault.jpg?v=63ceb22c&sqp=CIjsup4G&rs=AOn4CLCYQers5LqHQ1fZylYFRA6yJufj7g)](https://youtu.be/A09_2yy5f2o)

Special thanks to [@HiddenBladeBLD](https://github.com/HiddenBladeBLD) for putting together this guide for me.

## Step 1: EmuDeck
Downloading and installing Emudeck and adding your Games

1. Go to https://www.emudeck.com within your browser on the SteamDeck.

2. Copy the file that you have just downloaded to your desktop and double click it to install Emudeck. (It will not work if the file is not copied to the desktop)

3. Select Easy mode and click on "Continue" 

4. Choose where you would like your roms to be stored and hit "Continue"

5. Choose if you would like to install Homebrew games provided for free by Emudeck and select "Finish"

6. Wait for the installation to finish and then click on "Exit"

7. Cemu has now Installed 11 Emulators, these will not show up in gaming mode and need to be added as Non Steam Games before they show up there. 
   This can be done by opening Steam in Desktop mode and then clicking on "+ADD A GAME" in the bottom left of steam and then clicking on "Add a Non-Steam Game" and then selecting the following as per the emulation you want to do and clicking on "ADD SELECTED PROGRAMS":
   
   Cemu Emudeck (WiiU Emulation)
   Citra (3DS Emulation)
   Dolphin Emulator (Wii and Gamecube Emulation)
   Duckstation (PS1 Emulation)
   PCSX2 (PS2 Emulation)
   PPSSPP (PSP Emulation)
   PrimeHack (Dolphin variant designed for Metroid Prime Emulation)
   Retroarch (Retro Console Emulation)
   RSPC3 (PS3 Emulation)
   yuzu EmuDeck (Switch Emulation)
   Xemu (Xbox Emulation)

8. Depending on where you chose to save your games (on the SD card or internal storage) the games will need to be put into different file paths.
   
   PLEASE NOTE that each of these File Paths has many different folders in them and you will need to put the roms in the right folder based on the Console that the game is supposed to be run on.
   
   For the SD Card that would be "primary" > "Emulation" > "roms"
   
   For the Internal Storage this can be found under "Home" > "Emulation" > "roms"

9. In order to run certain Emulators you might need bios files, these need to be placed in the correct folders for the console but can be found in the following locations 
   
   PLEASE NOTE: As this could be construed as piracy we are unable to provide these to you but a bit of searching on the internet goes a long way.
   
   SD Card: "primary" > "Emulation" > "bios"
   
   Internal Storage: "Home" > "Emulation" > "bios"



## Step 2: Steam ROM Manager
Using Steam Rom Manager to Add all your Games to Steam:

Having successfully added all your games (and the device bios) into the correct folders you can now use Steam Rom Manager to add all your games to Steam including the games Box art.

1. Open up Steam Rom Manager by clicking on the SteamDeck symbol in the bottom left of your screen in Desktop mode, Navigating to "All Applications" and then clicking on "Steam Rom Manager"

2. To add all your games to Steam simply Click on "Preview" at the top left and then on "Generate app list" Make sure Steam is not running (If it is please close it now by rightclicking on the Steam Symbol in the bottom right and selecting "Exit Steam")
   
   Now click on "Save app list"
   
   That's it all your games shold now show up in gaming mode.



## Step 3: Replace Yuzu Emulator
Replacing the Yuzu Emulator with a more recent version

1. Navigate to https://pineappleea.github.io 

2. Select the latest version and download the App Image

3. Open the File browser and go to Downloads and rename the App Image to "yuzu.AppImage"
   
4. Now click on "Split at the top right and navigate to "Home" > "Applications"

5. Rename the yuzu.AppImage that is in applications to "yuzu.AppImage.Old"

6. Move the yuzu.AppImage from "Downloads" to "Applications"



## Step 4: PowerTools
Installing Decky Loader and Power Tools

1. Open Emudeck by going to the Steamdeck Symbol in the bottom left on your Screen in Desktop Mode, then click on "All Applications" and scroll down until you see "EmuDeck" click on this once.

2. With EmuDeck open click on "Tools & stuff"

3. Click on "PowerTools" then when prompted set your sudo password, afterwards enter your sudo password to install PowerTools.

4. Now Switch to Gaming Mode by double clicking on "Return to Gaming Mode" on your desktop.

5. In Gaming mode Press the Triple Dot button on the right bottom side of your SteamDeck.

6. With the right sidepanel open on the SteamDeck click on the Store icon right below your Profile Picture.

7. Scroll down until you see powertools and hit A twice to Install it


# Step 5: CryoUtilities
Installing and using CryoUtilities

1. Navigate to https://github.com/CryoByte33/steam-deck-utilities and scroll down until you see the "Easy" section under "Install"

2. Click the Link (as shown in the image)
![Clik this link](cryoutilities-link.png)

3. Hit "CTRL" and "S" together to save this as a file.

4. Open your filebrowser, navigate to "Downloads" and move the file you just downloaded called "Install Cryo Utilities" to your desktop.

5. Double click on the "Install Cryo Utilities" file to install it.

6. Run the newly Installed "CryoUtilities" Application from your desktop by double clicking it. 

7. Accept that you want to run CryoUtilities by clicking "Yes" in the Disclaimer.

8. Enter your sudo password and click on "OK"

9. When asked if you want to change the Swap File size click on "Yes"

10. Select 16 and click "OK" and then click okay again when the process is finished.

11.  When asked if you want to change swappiness click "Yes"

12.  Select "1" in the Swappiness Value window and click "OK"

13. When asked if you want to run TRIM click "Yes" and wait for the process to complete, then click "OK"


## Step 6: VRAM Settings
Changing the VRAM settings from 1 GB to 4GB

1. Turn off your Steam Deck

2. Hold the "Power on" and the "Volume up" Button to go to the Steamdecks Bios

3. Navigate to "Setup Utility" and enter with the "A" button.

4. Go down to the "Advanced Tab" and use "dpad right" to enter the advanced tabs settings.

5. Scroll down to "UMA Frame buffer Size" using the dpad then click "A" and scroll down to 4G and press "A" again

6. Click the "Select" button (looks like 2 windows) at the top left above the left stick to save and exit.