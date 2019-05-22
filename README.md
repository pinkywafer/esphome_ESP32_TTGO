# esphome_ESP32_TTGO

sets up the white TTGO camera / PIR / button / LCD for home assistant in esphome

The pir is exposed to home assistant as a motion binary sensor
The button is exposed as a binary sensor
The camera is exposed as a camera
The LCD simply displays the date and time from home assistant
NOTE that you will need to install a font file (times-new-roman.ttf) in the fonts/ directory
There are two font entries in my yaml - these are the same font, but in two different sizes as I have the date displayed smaller

Note the I2C setup is used by the LCD


---
<a href="https://www.buymeacoffee.com/V3q9id4" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/purple_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>
