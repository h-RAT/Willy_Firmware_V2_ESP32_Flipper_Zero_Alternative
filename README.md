# Willy_Firmware_CC1101 (Work in progress)

<strong>Idea, development and implementation of this firmware:</strong> h-RAT (https://github.com/h-RAT/).
<br><br>
<strong>Discord: h-RAT#2465</strong>
<br><br>
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Y8Y1L3OUQ)

# Preview
<div align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Initialization.png" alt="Initialization"> 
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Device.png" alt="Device">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Main.png" alt="Main">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Signal.png" alt="Signal">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Transmit.png" alt="Transmit">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Misc.png" alt="Misc">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Tesla.png" alt="Tesla">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/DeBruijn.png" alt="DeBruijn">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Jukebox.png" alt="Jukebox">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SD.png" alt="SD Card">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Settings.png" alt="Settings">
</div>

<br>

# Summary
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
- [ ] Rolljam
- [ ] Rollback
- [ ] Jammer

Device features:
- [x] Touch Screen
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
