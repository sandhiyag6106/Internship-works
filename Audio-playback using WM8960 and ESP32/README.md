Overview- Audio playback by interfacing WM8960 with ESP32 S3 devkit. Audio files stored in SD card module and played through headphones/speakers.

Components used - ESP32 S3 devkit, WM8960 audio codec, SD Card module, SD Card, Headphones/speaker, Breadboard, Connecting wires.

Software used - Arduino IDE.

Project Insights - Challenges faced were with SD card module and audio codec configuration. SD card was not functioning properly, which was resolved by rewiring it to interface ESP32.
Additionally, audio codec had issues related to clock configuration, which were addressed by adjusting the clock settings and wiring.
These were resolved by implementing I2S communication and storing the audio file in wav format on SD card, enabling playback through the headphone/speaker. 
