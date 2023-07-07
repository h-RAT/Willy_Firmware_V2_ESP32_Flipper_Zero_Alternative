# Willy_Firmware_CC1101_ESP32_Display_Touchscreen (Work in progress)

<strong>Idea, development and implementation of this firmware:</strong> h-RAT (https://github.com/h-RAT/).
<br><br>
<strong>Discord: h-RAT#2465</strong>
<br><br>
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Y8Y1L3OUQ)

# Preview

Demo: https://www.youtube.com/watch?v=r5-hpoPlQkU

<div align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/IMG_20230624_181105.jpg" width="500" alt="Willy"> 
</div>
<br>
<div align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/1.png" alt="Loading"> 
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/2.png" alt="Main">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/3.png" alt="Record">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/4.png" alt="Transmit">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/5.png" alt="Misc">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/6.png" alt="Scanner">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/7.png" alt="SD Card">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/8.png" alt="Settings">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/9.png" alt="Device">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/10.png" alt="Signal">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/11.png" alt="Bruteforce">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/14.png" alt="Tesla">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/15.png" alt="DeBruijn">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/16.png" alt="Jukebox">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/17.png" alt="Save">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/18.png" alt="Jammer">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/19.png" alt="Attack">
</div>

# Summary<a id="summary"></a>
<li><strong><a href="#introduciton">Introduction</a></strong></li>
<li><strong><a href="#disclaimer">Disclaimer</a></strong></li>

# Introduction<a id="introduction"></a>
Willy Firmware is an alternative to Flipper Zero.

This firmware allows the following attacks:
- [x] Record Signal
- [x] Save Signal to SD Card
- [x] Send Last Signal
- [x] Transmit .SUB File from SD Card (Protocol: RAW, Princeton, CAME, NiceFLO, GateTX, Holtek HT12X)
- [x] Transmit Decimal*
- [x] Signal Scanner
- [x] Bruteforce Decimal*
- [x] Bruteforce DeBruijn**
- [x] Bruteforce Jukebox***
- [x] Open Tesla Charge Door (EU)
- [x] Open Tesla Charge Door (US)
- [x] Rolljam
- [x] Rollback
- [x] Jammer

Device features:
- [x] ESP32 T-Display-S3
- [x] Touchscreen Display
- [x] Battery Indicator
- [x] Battery Charger
- [x] SD Card Module
- [x] CC1101 Module

<br>

*Protocol: Princeton (24bits), Holtek HT12X (12bits), CAME (12bits), CAME (18bits), CAME (24bits), CAME (25bits), SMC5326 (25bits), Nice FLO (12bits), Nice FLO (24bits), GateTX (24bits),
<br><br>
**DeBruijn: Linear Multicode (10bits), Stanley Multicode (10bits), Chamberlain (9bits), Linear Moorematic (8bits),
<br><br>
***Jukebox: Free Credit, Pause Song, Skip Song, Volume UP, Volume DOWN, Power OFF, Lock Queue,

# Disclaimer<a id="disclaimer"></a>

This device is a basic device for professionals and cybersecurity enthusiasts.

We are not responsible for the incorrect use of this device.

Be careful with this device and the transmission of signals. Make sure to follow the laws that apply to your country.
