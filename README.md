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

<h2>Record</h2>

- [x] Record Signal
- [x] Send Last Signal
- [x] Save Last Signal	

<h2>Transmit</h2>

- [x] Send Key*

<h2>*Protocol List</h2>

- [x] Ansonic (12bit)
- [x] BETT (18bit)
- [x] CAME (12bit, 18bit, 24bit, 25bit)
- [x] Clemsa (18bit)
- [x] Doitrand (37bit)
- [x] Dooya (40bit)
- [x] FAAC SLH (64bit)
- [x] GateTX (24bit)
- [x] Holtek HT12X (12bit)
- [x] Holtek (40bit)
- [x] Honeywell (48bit)
- [x] Hormann (44bit)
- [x] IntertechnoV3 (32bit)
- [x] KeeLoq (64bit)
- [x] Kinggates (89bit)
- [x] LinearDelta3 (8bit)
- [x] Linear (10bit)
- [x] Magellan (32bit)
- [x] Marantec (49bit)
- [x] Nero Radio (56bit)
- [x] Nero Sketch (40bit)
- [x] Nice FLO (12bit, 24bit)
- [x] PhoenixV2 (52bit)
- [x] Power Smart (64bit)
- [x] Princeton (24bit)
- [x] Security+ V1 (21bit)
- [x] SMC5326 (25bit)
- [x] Starline (64bit)
- [x] UNILARM (25bit)

<h2>Bruteforce</h2>

- [x] Bruteforce Key**

<h2>**Protocol List</h2>

- [x] Ansonic (12bit)
- [x] CAME (12bit)
- [x] Holtek HT12X AM (12bit)
- [x] Holtek HT12X FM (12bit)
- [x] LinearDelta3 (8bit)
- [x] Linear (10bit)
- [x] Nice FLO (12bit)
- [x] Princeton (24bit)
- [x] SMC5326 (25bit)
- [x] UNILARM (25bit)

<h2>Tesla</h2>

- [x] Send EU Tesla Charge Door
- [x] Send US Tesla Charge Door

<h2>DeBruijn</h2>

- [x] Send Linear Multicode
- [x] Send Stanley Multicode
- [x] Send Charmberlain
- [x] Send Linear MooreMatic

<h2>Jukebox</h2>

- [x] Send Free Credit
- [x] Send Pause Song
- [x] Send Skip Song
- [x] Send Volume UP
- [x] Send Volume DOWN
- [x] Send Power OFF
- [x] Send Lock Queue

<h2>Attack Switch Mode</h2>

- [x] Receiver/Jammer mode (Need two devices to perform the attacks properly)

<h2>Attack : Receiver : Rolljam</h2>

- [x] Set Jammer Power
- [x] Set Send First Signal Auto.
- [x] Start Rolljam Attack
- [x] Send First Signal
- [x] Send Second Signal

<h2>Attack : Receiver : Rollback</h2>

- [x] Set Jammer Power
- [x] Set Num. Signal Required
- [x] Set Time Frame
- [x] Start Rollback Attack
- [x] Send Sequence
- [x] Save Sequence

<h2>Jammer</h2>

- [x] Set Jammer Power

<h2>Scanner</h2>

- [x] Start Hoop Freq Scan
- [x] Set Frequency Found

<h2>SD Card</h2>

- [x] Send .sub file***

<h2>***Protocol List</h2>

- [x] RAW
- [x] AlutechAT
- [x] Ansonic
- [x] BETT
- [x] CAME 
- [x] Clemsa
- [x] Doitrand
- [x] Dooya
- [x] FAAC SLH
- [x] GateTX
- [x] Holtek HT12X
- [x] Holtek
- [x] Honeywell
- [x] Hormann
- [x] IntertechnoV3
- [x] KeeLoq
- [x] Kinggates
- [x] LinearDelta3
- [x] Linear
- [x] Magellan
- [x] Marantec
- [x] Nero Radio
- [x] Nero Sketch
- [x] Nice FLO
- [x] PhoenixV2
- [x] Power Smart
- [x] Princeton
- [x] Security+ 1.0
- [x] Security+ 2.0
- [x] SMC5326
- [x] Starline
- [x] UNILARM

<h2>Settings</h2>

- [x] Set Frequency
- [x] Set Preset

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

<div align="flex">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/IMG_20230810_164448.jpg" width="500" alt="Willy">
</div>

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
