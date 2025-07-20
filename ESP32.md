First, Open Arduino IDE!

1. In your Arduino IDE, go to File> Preferences
2. Enter the following into the “Additional Board Manager URLs” field:
   https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
   then click "ok"
3. Open the Boards Manager. Go to Tools > Board > Boards Manager…
4. Search for ESP32 and press install button for the “ESP32 by Espressif Systems“

*If you try to upload a new sketch to your ESP32 and you get this error message “A fatal error occurred: Failed to connect to ESP32: Timed out… Connecting…“. It means that your ESP32 is not in flashing/uploading mode.

<b>Press boot button in esp32 board when IDE running Connecting.........</b>

*If you get the error “COM Port not found/not available”, you might need to install the CP210x Drivers:
https://www.silabs.com/documents/public/software/CP210x_Universal_Windows_Driver.zip
