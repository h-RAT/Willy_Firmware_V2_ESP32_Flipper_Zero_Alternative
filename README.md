# Introduction<a id="introduction"></a>
Willy is an alternative to Flipper Zero based on an ESP32.

<div align="flex">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/IMG_20230624_181105.jpg" width="500" alt="Willy">
</div>

<br>

<strong>Idea, development and implementation of this firmware:</strong> h-RAT (https://github.com/h-RAT/)
<br><br>
<strong>Discord: h-RAT#2465</strong>
<br><br>
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Y8Y1L3OUQ)

<br>

# Features<a id="features"></a>

- [x] Record Signal
- [x] Send Last Signal
- [x] Save Signal to SD Card
- [x] Send Signal from SD Card*
- [x] Scanner
- [x] Jammer
- [x] Bruteforcer**
- [x] DeBruijn***
- [x] Jukebox****
- [x] Tesla Charge Door
- [x] Rolljam (Requires two devices to perform this attack)
- [x] Rollback (Requires two devices to perform this attack)

<br>

*Flipper Zero .SUB File (RAW, AlutechAT-4N, Ansonic, BETT, CAME, FAAC, GateTX, Holtek, Holtek HT12X, Honeywell, Hormann, Intertechno_V3, KeeLoq, Linear, Linear Delta 3, MegaCode, Nice FLO, Princeton, SMC5326, Starline, UNILARM)
<br><br>
**Bruteforcer: CAME (12bit), Nice FLO (12bit), Ansonic (12bit), Holtek FM (12bit), Holtek AM (12bit), Chamberlain (9bit), Chamberlain (8bit), Chamberlain (7bit), Linear (10bit), Linear Delta 3 (8bit), UNILARM (25bit), SMC5326 (25bit), Princeton (24bit)
<br><br>
***DeBruijn: Linear Multicode (10bits), Stanley Multicode (10bits), Chamberlain (9bits), Linear Moorematic (8bits),
<br><br>
****Jukebox: Free Credit, Pause Song, Skip Song, Volume UP, Volume DOWN, Power OFF, Lock Queue,

<br>

# Preview<a id="preview"></a>

   <div>
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Loading.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Function.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Main.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Misc.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Device.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Theme.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Record.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Signal.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SD.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Transmit.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Settings.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Scanner.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Bruteforce.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Jammer.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Tesla.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/DeBruijn.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Jukebox.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Attack.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/JammerRolljam.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Rolljam.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/ConfigRolljam.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Rollback.png" width="170" alt="Willy">
    	<img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/ConfigRollback.png" width="170" alt="Willy">
   </div>
  
<br>
  Demo: https://www.youtube.com/watch?v=r5-hpoPlQkU
  
<br>

# Build<a id="build"></a>

Board:
- [x] 1x ESP32-S3 T-Display Touch Version - Soldered | https://www.aliexpress.us/item/3256804741686185.html

CC1101 Shield:
- [x] 1x S3 T-Display TF/SD Shield - Female | https://www.aliexpress.us/item/3256804956138540.html
- [x] 1x CC1101 V2.0 Module | https://www.aliexpress.us/item/2251832873028557.html
 
IR Shield: (soon)

<br>

# Firmware<a id="firmware"></a>

Due to a lot of abuse, the firmware is no longer free.

<br>

Link: https://willyfirmware.mysellix.io/product/64ca6015d3acc

<br>

Add me on discord for more info.

<br>

# Disclaimer<a id="disclaimer"></a>

This device is a basic device for professionals and cybersecurity enthusiasts.

We are not responsible for the incorrect use of this device.

Be careful with this device and the transmission of signals. Make sure to follow the laws that apply to your country.
