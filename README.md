# Sour Apple 
Original by: https://github.com/RapierXbox/ESP32-Sour-Apple/tree/main


!!! Modded for comlipe with NimBLE library in arduino ide for esp32


NIM_BLE :
https://github.com/h2zero/NimBLE-Arduino
https://github.com/h2zero/NimBLE-Arduino/archive/refs/tags/1.4.1.zip


# IOS17 Crash Exploit
The Exploit was original found by ECTO-1A and then refactored by WillyJL. I portet it to the ESP32 from the Flipper Zero Xtreme firmware. Scripts for the ESP8266 are coming soon. The exploit crashes when the device is locked on the homescreen.
# Disclaimer
Only use this on devices you own or when you have permisson to use it. I know you gonna be trolling people but dont crash old peoples iPhones. They are not gonna know what to do and so they gonna pay way to much money to fix it.

This project is made only for educational purposes and is not made to break laws and or personal gain. The project has no warranty so if your break any of your devices the author is not responsable.
# Testing
This was only testetet on a ESP-WROOM-32 on:
-iPhone 12 Pro -   iOS 17.0 (21A329)
# Behavior
The iPhone after around 30 seconds of spamming with some popups the iPhone starts to freeze. After a random looking amount of time the iPhone turns completly black and you can now force restart it (Volume UP, Volume Down, Hold power button). Sometimes the iPhone restarts by itself. In this procedure the ESP shouldnt get hot.

