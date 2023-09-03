# Introduction<a id="introduction"></a>
Willy is an alternative to Flipper Zero based on an ESP32.

<div align="flex">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/IMG_20230624_181105.jpg" width="500" alt="Willy">
</div>

<br>

<strong>Idea, development and implementation of this firmware:</strong> h-RAT (https://github.com/h-RAT/)
<br>

# Summary

<li><strong><a href="#introduction">Introduction</a></strong></li>
<li><strong><a href="#features">Features</a></strong></li>
<ul>
<li><a href="#subghz">SubGhz</a></li>
<li><a href="#infrared">Infrared</a></li>
</ul>

<li><strong><a href="#video">Video</a></strong></li>
<li><strong><a href="#build">Build</a></strong></li>
<li><strong><a href="#firmware">Firmware</a></strong></li>
<li><strong><a href="#contact">Contact</a></strong></li>
<li><strong><a href="#disclaimer">Disclaimer</a></strong></li>

# Features<a id="features"></a>

<h2>SubGhz -> Record</h2><a id="subghz"></a>

- [x] Record Signal
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Record.png" width="170" alt="Willy">
</div>

- [x] Send Last Signal
- [x] Save Last Signal	
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Signal.png" width="170" alt="Willy">
</div>
   
<h2>SubGhz -> Transmit</h2>

- [x] Send Key*
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Transmit.png" width="170" alt="Willy">
</div>

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

<h2>SubGhz -> Bruteforce</h2>

- [x] Bruteforce Key**
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Bruteforce.png" width="170" alt="Willy">
</div>

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

<h2>SubGhz -> Tesla</h2>

- [x] Send EU Tesla Charge Door
- [x] Send US Tesla Charge Door
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Tesla.png" width="170" alt="Willy">
</div>

<h2>SubGhz -> DeBruijn</h2>

- [x] Send Linear Multicode
- [x] Send Stanley Multicode
- [x] Send Charmberlain
- [x] Send Linear MooreMatic
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/DeBruijn.png" width="170" alt="Willy">
</div>

<h2>SubGhz -> Jukebox</h2>

- [x] Send Free Credit
- [x] Send Pause Song
- [x] Send Skip Song
- [x] Send Volume UP
- [x] Send Volume DOWN
- [x] Send Power OFF
- [x] Send Lock Queue
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Jukebox.png" width="170" alt="Willy">
</div>

<h2>SubGhz -> Attack Switch Mode</h2>

- [x] Receiver/Jammer mode (Need two devices to perform the attacks properly)
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Attack.png" width="170" alt="Willy">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/JammerRolljam.png" width="170" alt="Willy">
</div>

<h2>SubGhz -> Attack : Receiver : Rolljam</h2>

- [x] Set Jammer Power
- [x] Set Send First Signal Auto.
- [x] Start Rolljam Attack
- [x] Send First Signal
- [x] Send Second Signal
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Rolljam.png" width="170" alt="Willy">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/ConfigRolljam.png" width="170" alt="Willy">
</div>

<h2>SubGhz -> Attack : Receiver : Rollback</h2>

- [x] Set Jammer Power
- [x] Set Num. Signal Required
- [x] Set Time Frame
- [x] Start Rollback Attack
- [x] Send Sequence
- [x] Save Sequence
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Rollback.png" width="170" alt="Willy">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/ConfigRollback.png" width="170" alt="Willy">
</div>

<h2>SubGhz -> Jammer</h2>

- [x] Set Jammer Power
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Jammer.png" width="170" alt="Willy">
</div>

<h2>SubGhz -> Scanner</h2>

- [x] Start Hoop Freq Scan
- [x] Set Frequency Found
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Scanner.png" width="170" alt="Willy">
</div>

<h2>SubGhz -> SD Card</h2>

- [x] Send .sub file***
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SD.png" width="170" alt="Willy">
</div>

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

<h2>SubGhz -> Settings</h2>

- [x] Set Frequency
- [x] Set Preset
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Settings.png" width="170" alt="Willy">
</div>

<h2>Infrared -> Universal Remotes</h2><a id="infrared"></a>

- [x] TV
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/TV.png" width="170" alt="Willy">
</div>

- [x] Digital Signs
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/DigitalsSigns.png" width="170" alt="Willy">
</div>

- [x] Projectors
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Projectors.png" width="170" alt="Willy">
</div>

- [x] Audio
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Audio.png" width="170" alt="Willy">
</div>

- [x] LED
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/LED.png" width="170" alt="Willy">
</div>

- [x] Fans
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Fans.png" width="170" alt="Willy">
</div>

<h2>Infrared -> Learn (work in progress - soon)</h2>

- [x] Receive IR Signal*
- [x] Save Last IR Signal
- [x] Send Last IR Signal
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Learn.png" width="170" alt="Willy">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SignalIR.png" width="170" alt="Willy">
</div>

<h2>*Protocol List</h2>

- [x] NEC / NEC16
- [x] Kaseikyo
- [x] Sony
- [x] Samsung
- [x] RC5
- [x] RC6

<h2>Device</h2>

- [x] Set Theme Color
- [x] Device Information
<br><br><div>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Function.png" width="170" alt="Willy">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Infrared.png" width="170" alt="Willy">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Universal.png" width="170" alt="Willy">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Main.png" width="170" alt="Willy">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Misc.png" width="170" alt="Willy">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Theme.png" width="170" alt="Willy">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Device.png" width="170" alt="Willy">
</div>

# Video<a id="preview"></a>

  Demo: https://www.youtube.com/watch?v=r5-hpoPlQkU
  <br>
  Demo: https://www.youtube.com/shorts/5iebprjgEjE
  
# Build<a id="build"></a>

<div align="flex">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/IMG_20230810_164448.jpg" width="500" alt="Willy">
</div>

<br>

Board:
- [x] 1x ESP32-S3 T-Display Touch Version - Soldered | https://www.aliexpress.us/item/3256804741686185.html

CC1101 Shield:
- [x] 1x S3 T-Display TF/SD Shield - Female | https://www.aliexpress.us/item/3256804956138540.html
- [x] 1x CC1101 V2.0 Module | https://www.aliexpress.us/item/2251832873028557.html
 
IR Shield:
- [x] 1x S3 T-Display TF/SD Shield - Female | https://www.aliexpress.us/item/3256804956138540.html
- [x] 1x Infrared Receiver TSOP4838 | https://www.aliexpress.us/item/1005004481948853.html
- [x] 2x Infrared LED TSAL6400 | https://www.aliexpress.us/item/32670031000.html
- [x] 2x Transistor 2N4401 | https://www.aliexpress.us/item/1005005484591463.html

# Firmware<a id="firmware"></a>

Due to a lot of abuse, the firmware is no longer free.

<br>

Link: https://willyfirmware.mysellix.io/product/64ca6015d3acc

<br>

Add me on discord for more info.

# Contact<a id="contact"></a>

- [x] Discord: h-RAT#2465

# Disclaimer<a id="disclaimer"></a>

This device is a basic device for professionals and cybersecurity enthusiasts.

We are not responsible for the incorrect use of this device.

Be careful with this device and the transmission of signals. Make sure to follow the laws that apply to your country.
