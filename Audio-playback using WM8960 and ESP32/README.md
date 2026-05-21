Overview- Audio playback by interfacing WM8960 with ESP32 S3 devkit. Audio files stored in SD card module and played through headphones/speakers.
Components used - ESP32 S3 devkit, WM8960 audio codec, SD Card module, SD Card, Headphones/speaker, Breadboard, Connecting wires.
Software used - Arduino IDE.
Project Insights - Challenges faced were SD card module was not working properly, so I rewired to correctly interface with ESP32.
The audio codec had issues related to clock configuration.
These were resolved using I2S communicatio nand audio file in wav format was uploaded to SD card and played through the headphone/speaker. 
