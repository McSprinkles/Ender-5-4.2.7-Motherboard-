Follow this guy's video (highly recommended – it's clear and visual):
https://www.youtube.com/watch?v=-pZmeRf-XNs

OR – Written Steps:

Flashing the Screen (DWIN/DGUS display):
Remove the bottom panel of the printer to access the screen's SD card slot.
Copy the DWIN_SET folder (not just the files inside – the whole folder) to the root of a microSD card.
Turn the printer completely off.
Insert the microSD card into the slot on the back/bottom of the screen.
Turn the printer on.
The screen will flash a series of images/colors and eventually show "Complete" or "Update Success".
Once it says complete, turn the printer off, remove the SD card, and reassemble the panel.

Flashing the Printer Mainboard (bugfix-2.x firmware):
Copy the file Firmware_Bugfix_V4_Modded.bin to the root of an SD card (no folder, just the .bin file directly on the card).
Turn the printer completely off.
Insert the SD card into the printer's main SD card slot (usually on the front or side).
Turn the printer on.
The printer will beep several times and the screen will go blank or show flashing progress – it will automatically reboot when finished (usually takes 30–60 seconds).

VERY IMPORTANT – SD Card Formatting (this is the #1 reason it fails):Use a ≤16GB SD card (8GB is ideal – larger cards often cause issues).
Format it as FAT32 with 4096 bytes (4KB) allocation unit size.
Use Windows formatter or SD Card Formatter tool (do NOT quick format if possible).
Card must be completely empty except for DWIN_SET folder or the .bin file