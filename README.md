# Micro-controllers

## Arduino IDE

1. Install the current upstream Arduino IDE at the 1.8 level or later. The current version is at the [Arduino website](http://www.arduino.cc/en/main/software). (NOTE: MacOS may require that you install separate drivers to interact with your board. You will get error messages that occur when the IDE attempts to upload code).

2. Start Arduino and open Preferences window.

3. Copy all folders in the `lib` directory to your Arduino Libraries Directory,
- in MacOS, it is `~/Documents/Arduino/libraries`
- in Linux, it is `~/Arduino/libraries` 
- in Windows, it is `Documents/Arduino/libraries` 

4. Open the corresponding example

5. In the Arduino Application, navigate to the Board Manager menu ("Tools => Board => Board Manager"), search for `esp32`, and make sure that you install the latest version. After you do this, you can select the board you have from the list of boards in the "ESP32 Arduino" menu ("Tools=> Board => ESP32 Arduino"). It's very important to note that the list of boards is NOT in alphabetical order. Look for the board you are working with carefully in the list. 

6. `T-Beam` users can choose `TTGO T-Beam`, `lora32(T3)` users can choose `ESP32 Dev Module` , `T-Motion` users choose `Nucleo_l073RZ`,`T3-S3-V1.0`and `T-BeamS3 Supreme` users can selected `ESP32S3 Dev Module`.

7. Select the port of the board in the port

8. Please uncomment the `utility.h` file above each sketch based on your board model, otherwise compilation will report an error

9. Upload

10. Enjoy 