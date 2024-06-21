<h1 align="center"> <code>Willy Firmware V2</code> - Flipper Zero alternative with ESP32</h1><a id="introduction"></a>

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Logo.png">
</p>

<h2 align="center">
  <a href="#introduction">Introduction</a> | <a href="#features">Features</a> | <a href="#build">Build</a> | <a href="#contact">Contact</a> | <a href="#disclaimer">Disclaimer</a>
</h2>

This firmware is an alternative to Flipper Zero for ESP-32, and is always updated from the original Flipper ideas, making it the most stable alternative.

<p align="center">
  <a href="https://discord.gg/VqsUsPQSmP"><img src="https://discordapp.com/api/guilds/1169681522715000873/widget.png?style=banner2" alt="Discord Banner 3"/></a>
</p>

<h4 align="center">Website: https://willy-firmware.com/</h4>

-----

<br>
<h1 align="center">What makes it special?</h1>

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/IMG_20230624_181105.jpg" width="500" alt="Willy">
</p>

We have spent many hours perfecting this code even further, and getting the most out of it.

The goal of this firmware is to be able to benefit from the same functions as the Flipper Zero but on an ESP32, which is cheaper, and easier to obtain in some countries, as well as to regularly bring out amazing updates based on what the community wants, with a real understanding of what is happening. Fixing regularly talked about bugs and expanding capabilities with exciting new features and, most importantly, ensuring the simplest user experience possible.

<br>

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Home.png">
</p>

<br><br>
- <h4>Feature-rich: We include all common applications (SubGhz/Infrared/BLE/WiFi) in the firmware as well as new features.</h4>

- <h4>Stable: Many hours have been spent rewriting core parts of the firmware as well as some of its apps to ensure stability.</h4>

<br><br>

-----

<h1 align="center">Features:</h1><a id="features"></a>

### #SubGhz

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SubGhz1.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SubGhz2.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SubGhz3.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SubGhz4.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SubGhz5.png">
</p>

-----

- Read RAW:<br>
Reads and decode signals in a raw format, including signals from remotes with unknown protocols. (You can save 30 signals in the memory)

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Read_RAW1.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Read_RAW2.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Read_RAW3.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SettingsRSSI.png"> 
</p>

From there you can send it or save it on the sd card for use it later. 

-----

- Read:<br>
Reads and decodes signals based on known protocols. If the protocol is static, Willy decode the signal. (You can save 30 signals in the memory)

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Read1.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Read2.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Read3.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SettingsRSSI.png"> 
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Read4.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Read5.png">
</p>

From there you can send it or save it on the sd card for use it later. 

<br>

```txt
[Supported decoders]

* Ansonic (12bit)
* BETT (18bit)
* CAME (12bit)
* CAME (18bit)
* CAME (24bit)
* CAME (25bit)
* Chamberlain (7bit)
* Chamberlain (8bit)
* Chamberlain (9bit)
* Clemsa (18bit)
* Doitrand (37bit)
* Dooya (50bit)
* FAAC SLH (64bit)
* GateTX (24bit)
* Hormann HSM (44bit)
* KeeLoq (64bit)
* Linear (10bit)
* Magellan (32bit)
* Marantec (49bit)
* Nice FLO (12bit)
* Nice FLO (24bit)
* Princeton (24bit)
* Starline (64bit)
```

<br>

-----

- Transmit:<br>
Generate and send signal based on known protocol and key.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Transmit.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SettingsRepeat.png">
</p>

From there you can send it or save it on the sd card for use it later. 

<br>

```txt
[Supported protocols]

* Alutech AT-4N (72bit)
* Ansonic (12bit)
* BETT (18bit)
* CAME Atomo (62bit)
* CAME TWEE (54bit)
* CAME (12bit)
* CAME (18bit)
* CAME (24bit)
* CAME (25bit)
* Chamberlain (7bit)
* Chamberlain (8bit)
* Chamberlain (9bit)
* Clemsa (18bit)
* Doitrand (37bit)
* Dooya (40bit)
* Faac SLH (64bit)
* GateTX (24bit)
* Genie (64bit)
* Holtek_HT12X (12bit)
* Holtek (40bit)
* Honeywell (48bit)
* Hormann HSM (44bit)
* Hormann BiSecur (176bit)
* Intertechno_V3 (32bit)
* KeeLoq (64bit)
* KIA (61bit)
* KingGates Stylo4k (89bit)
* LinearDelta3 (8bit)
* Linear (10bit)
* Magellan (32bit)
* Marantec (49bit)
* Mastercode (36bit)
* Megacode (24bit)
* Nero Radio (56bit)
* Nero Sketch (40bit)
* Nice FLO (12bit)
* Nice FLO (24bit)
* Nice FloR-S (52bit)
* Phoenix_V2 (52bit)
* Power Smart (64bit)
* Princeton (24bit)
* Security+ 1.0 (21bit)
* Security+ 2.0 (62bit)
* SMC5326 (25bit)
* Somfy Keytis (80bit)
* Somfy Telis (56bit)
* Starline (64bit)
* UNILARM (25bit)
```

<br>

-----

- Scanner:<br>
When analysing, the device scanning signals strength (RSSI) at all the frequencies available in frequency configuration. 
Then displays the frequency with the highest RSSI value, with signal strength higher than than configured.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Scanner1.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Scanner2.png">
</p>

From there you can apply the found frequency for the general settings.

-----

- Jammer:<br>
This function generates noise. Be careful when using this feature and ensure you follow the laws in your country. This may cause interference and potentially disrupt the proper operation of some devices.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Jammer.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SettingsPower.png">
</p>

-----

- Bruteforce:<br>
If you know the protocol used for example by the garage door it's possible to generate all the codes and send them with the Willy. 

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Bruteforce1.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Bruteforce2.png">
</p>

<br>

```txt
[Supported protocols]

* CAME (12bit) - 303.87 mHz 
* CAME (12bit) - 307.80 mHz 
* CAME (12bit) - 315.00 mHz 
* CAME (12bit) - 330.00 mHz 
* CAME (12bit) - 433.92 mHz 
* CAME (12bit) - 868.35 mHz
* Nice FLO (12bit) - 433.92 mHz 
* Nice FLO (12bit) - 868.35 mHz
* Ansonic (12bit) - 433.07 mHz 
* Ansonic (12bit) - 433.92 mHz 
* Ansonic (12bit) - 434.07 mHz
* Holtek_HT12X (12bit) FM - 433.92 mHz (TE: 204μs) 
* Holtek_HT12X (12bit) AM - 433.92 mHz (TE: 433μs) 
* Holtek_HT12X (12bit) AM - 315.00 mHz (TE: 433μs) 
* Holtek_HT12X (12bit) AM - 868.35 mHz (TE: 433μs) 
* Holtek_HT12X (12bit) AM - 915.00 mHz (TE: 433μs)
* Chamberlain (9bit) - 300.00 mHz
* Chamberlain (9bit) - 315.00 mHz
* Chamberlain (9bit) - 390.00 mHz
* Chamberlain (9bit) - 433.92 mHz
* Chamberlain (8bit) - 300.00 mHz
* Chamberlain (8bit) - 315.00 mHz
* Chamberlain (8bit) - 390.00 mHz
* Chamberlain (7bit) - 300.00 mHz
* Chamberlain (7bit) - 315.00 mHz
* Chamberlain (7bit) - 390.00 mHz
* Linear (10bit) - 300.00 mHz
* Linear (10bit) - 310.00 mHz
* Linear Delta 3 (8bit) - 310.00 mHz
* UNILARM (25bit) - 330.00 mHz (TE: 209μs) // Note: Only dip switch combinations, not full 25bit bruteforce
* UNILARM (25bit) - 433.92 mHz (TE: 209μs) // Note: Only dip switch combinations, not full 25bit bruteforce
* SMC5326 (25bit) - 330.00 mHz (TE: 320μs) // Note: Only dip switch combinations, not full 25bit bruteforce
* SMC5326 (25bit) - 433.92 mHz (TE: 320μs) // Note: Only dip switch combinations, not full 25bit bruteforce
* Princeton (24bit) - 315.00 mHz (TE: 286μs) // Note: Only for 8 dip switch remote, not full 24bit bruteforce
* Princeton (24bit) - 330.00 mHz (TE: 286μs) // Note: Only for 8 dip switch remote, not full 24bit bruteforce
* Princeton (24bit) - 390.00 mHz (TE: 286μs) // Note: Only for 8 dip switch remote, not full 24bit bruteforce
* Princeton (24bit) - 433.92 mHz (TE: 286μs) // Note: Only for 8 dip switch remote, not full 24bit bruteforce
```

<br>

-----

- DeBruijn:<br>
Generate and send DeBruijn sequence for predefined garage door models.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/DeBruijn.png">
</p>

<br>

```txt
[Supported sequence]

* Linear Multicode - 300.00 mHz
* Linear Multicode - 310.00 mHz
* Linear Multicode - 390.00 mHz
* Linear Multicode - 433.92 mHz
* Stanley Multicode - 300.00 mHz
* Stanley Multicode - 310.00 mHz
* Stanley Multicode - 390.00 mHz
* Stanley Multicode - 433.92 mHz
* Charmberlain - 300.00 mHz
* Charmberlain - 310.00 mHz
* Charmberlain - 390.00 mHz
* Charmberlain - 433.92 mHz
* Linear MooreMatic - 300.00 mHz
* Linear MooreMatic - 310.00 mHz
* Linear MooreMatic - 390.00 mHz
* Linear MooreMatic - 433.92 mHz
```

<br>

From original Samy Kamkar Open Sesame

-----

- Tesla:<br>
Generate and send open charge door signal for Tesla.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Tesla.png">
</p>

<br>

```txt
[Supported region]

* EU - 433.92 mHz
* US - 315.00 mHz
```

<br>

-----

- Jukebox:<br>
Generate and send command for jukeboxes commonly found in bars.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Jukebox.png">
</p>

<br>

```txt
[Supported command]

* Free Credit - 433.92 mHz
* Pause Song - 433.92 mHz
* Skip Song - 433.92 mHz
* Volume UP - 433.92 mHz
* Volume DOWN - 433.92 mHz
* Power OFF - 433.92 mHz
* Lock Queue - 433.92 mHz
```

<br>

-----

- Rolljam:<br>
This function is a proof of concept.<br>RollJam is a method of capturing a rolling code key transmission by simultaneously intercepting the transmission and jamming the receivers window with another device; giving the attacker a valid rolling code for re-transmission. 

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Rolljam1.png">  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Rolljam2.png">  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Rolljam3.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SettingsRSSI.png"> 
</p>

<p align="center">
  <code>You need two devices to perform this P.O.C successfully.</code>
  <br><br>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/JamMode.png">
</p>

-----

- Rollback:<br>
This function is a proof of concept.<br>Rollback is a vulnerability found mostly in Honda vehicles. By capturing X valid unlock key fob signals, it allows remote attackers to perform unlock operations and force a resynchronization; giving the attacker the ability to unlock indefinitely.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Rollback1.png">  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Rollback2.png">  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Rollback3.png">  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Rollback4.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SettingsRSSI.png"> 
</p>

<p align="center">
  <code>You need two devices to perform this P.O.C successfully.</code>
  <br><br>
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/JamMode.png">
</p>

-----

- Saved File:<br>
Let's you to view the contents of your SD card and allows you to view and transmit your files.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SD_Card_Sub1.png">  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SD_Card_Sub3.png">  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SD_Card_Sub2.png">
</p>

<br>

```txt
[Supported protocols]

* RAW Data
* Alutech AT-4N (72bit)
* Ansonic (12bit)
* BETT (18bit)
* CAME Atomo (62bit)
* CAME TWEE (54bit)
* CAME (12bit)
* CAME (18bit)
* CAME (24bit)
* CAME (25bit)
* Chamberlain (7bit)
* Chamberlain (8bit)
* Chamberlain (9bit)
* Clemsa (18bit)
* Doitrand (37bit)
* Dooya (40bit)
* Faac SLH (64bit)
* GateTX (24bit)
* Genie (64bit)
* Holtek_HT12X (12bit)
* Holtek (40bit)
* Honeywell (48bit)
* Hormann HSM (44bit)
* Intertechno_V3 (32bit)
* KeeLoq (64bit)
* KIA (61bit)
* KingGates Stylo4k (89bit)
* LinearDelta3 (8bit)
* Linear (10bit)
* Magellan (32bit)
* Marantec (49bit)
* Mastercode (36bit)
* Megacode (24bit)
* Nero Radio (56bit)
* Nero Sketch (40bit)
* Nice FLO (12bit)
* Nice FLO (24bit)
* Nice FloR-S (52bit)
* Phoenix_V2 (52bit)
* Power Smart (64bit)
* Princeton (24bit)
* Security+ 1.0 (21bit)
* Security+ 2.0 (62bit)
* SMC5326 (25bit)
* Somfy Keytis (80bit)
* Somfy Telis (56bit)
* Starline (64bit)
* UNILARM (25bit)
```

<br>

-----

### #Infrared

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Infrared.png">
</p>

-----

- Learn:<br>
Point the LED of the remote at the IR receiver and just press the button which you want to capture. (You can save 30 signals in the memory)

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Learn1.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Learn2.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Learn3.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Learn4.png">
</p>

From there you can send it or save it on the sd card for use it later. 

-----

- Remote:<br>
Just a universal remote control for TVs, AUdio, Projectors, Fans, etc.. Works with a database defined in a file, require an SD card.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Remote1.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Remote2.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Remote3.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Remote_TV1.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Remote_TV2.png"> 
</p>

-----

- Tv-B-Gone:<br>
Just a universal remote control for TVs, works with the public TV-B-Gone database, does not require an SD card.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Tv-B-Gone.png">
</p>

<br>

```txt
[Supported region]

* EU - 139 signals
* NA - 139 signals
```

<br>

-----

- Saved File:<br>
Let's you to view the contents of /SD Card/infrared/ (the default place to save your remotes) and allows you to transmit it.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SD_Card_Infrared1.png">  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SD_Card_Infrared2.png">
</p>

<br>

```txt
[Supported protocols]
* RAW
* NEC
* NECext
* NEC42
* NEC42ext
* Kaseikyo
* RCA
* RC5X
* RC5
* RC6
* Samsung32
* SIRC
* SIRC15
* SIRC20
```

<br>

Q: My universal remote doesn't work here or doesn't work there or I want to control this or that but it's not in the Universal remotes and I don't have a remote for it
<blockquote>
<p>A: Use the IRDB. It contains thousands of remotes sorted by type (AC, TV, Fan..) and then by name (Samsung, Logitech..). Here is a <a href="https://github.com/logickworkshop/Flipper-IRDB" title="link">link</a> just copy the contents to /SD Card/infrared (I recommend using a SD card reader for it.)</p>
</blockquote>

Q: I want to write my own .ir files, how do I do that?
<blockquote>
<p>A: This: IRDB Never used it myself but if you want to write your own .ir files, you can do your own research on the usage of the formats and idk what not. You should be good using irdb though, but it's always nice to have a few contributors :)</p>
</blockquote>

<br>

-----

### #BLE

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Bluetooth.png">
</p>

-----

- BLE Spammer:<br>
This function is designed to flood Bluetooth Low Energy (BLE) devices with connection requests or packets. It can be utilized for testing the resilience and security of BLE devices, including those running on Apple (iOS) and Android platforms.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/BLE_Spam.png">
</p>


<br>

```txt
[Supported payloads]

* IOS 17 Lockup Crash
* Apple Action Modal
* Apple Device Popup
* Android Device Connect
* Samsung Buds Popup
* Samsung Watch Pair
* Windows Device Found
* BT Settings Flood
```

-----

- BLE Scanner:<br>
This feature is used to discover and monitor nearby Bluetooth Low Energy devices. It works by searching for advertising packets that BLE devices periodically broadcast to announce their presence.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/BLE_Scan1.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/BLE_Scan2.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/BLE_Scan3.png"> 
</p>


For each Bluetooth device found, the following information is displayed:

- Name
- MAC
- Potential Skimmer (https://learn.sparkfun.com/tutorials/gas-pump-skimmers/all)
- RSSI

<br>

-----

### #WiFi

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/WiFi.png">
</p>

-----

- SSID Spammer:<br>
This attack is a type of wireless network attack where an attacker floods a target area with fake SSID broadcast frames. The device sends out a large number of beacon frames, each containing a different fake SSID, with the intention of overwhelming nearby devices and networks.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/SSID_Spam.png">
</p>
<br>

```txt
[Supported payloads]

* Default
* Rick Roll
* Random
```

-----

- Sniffer:<br>
This feature is used to scan for WiFi networks and clients.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Sniffer1.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Sniffer2.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Sniffer3.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Sniffer4.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Sniffer5.png">
</p>

From here you have the possibility to start a deauth attack on a access point or particular station.

-----

- Deauth:<br>
This feature is used to disconnect devices from their WiFi network by sending deauth packets (deauthentication attack).

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Deauth1.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Deauth2.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Deauth3.png">
</p>

<br>

```txt
[Supported target]

* Access Point
* Station
```

-----

- Evil Portal:<br>
This function will turn your device into an open access point. When users try to connect to this access point they will be served a fake login screen. User data are sent to the Willy.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/EvilPortal1.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/EvilPortal2.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/EvilPortal3.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/EvilPortal4.png">
</p>

<code>Note: Place your custom html files into /SD Card/evilportal/</code> <br><br> 

<br>

Q: ESP32 Limitations ?
<blockquote>
<p>A: The ESP32 access point will not have internet access while hosting the portal, as a result there cannot be any requests for stylesheets or javascript such as CDNs for bootstrap and JQuery.

All HTML/CSS/JS must be in a single HTML file. This is due to the fact that the index.html kept in the memory of the esp32.

There is a 20k character limit for each HTML file.

The form data must be sent to the `/get` endpoint as a GET request with the params `email` & `password`. You can put any information you want in these two fields. For example the `email` param can contain a username instead, just keep the param name as `email`.

Please check the examples to get an idea of what this has to look like.</p>
</blockquote>

-----

### #Device

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Device1.png"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Device2.png">
</p>

-----

- About:<br>
Show information about the device.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/About.png">
</p>

-----

- Sleep Mode:<br>
You can turn off the device with the physical button located under the screen at the bottom left.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Sleep.png">
</p>

-----

- Color:<br>
Recolor all firmware icons and save the choice in memory.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Color.png">
</p>

-----

- Brightness:<br>
Adjust the display brightness and save the choice in memory.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Brightness.png">
</p>

-----

- PIN Code:<br>
You can configure a 4-digit PIN code to secure the device boot.<br><br>Default PIN: <code>0000</code>

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Edit_PIN.png">
</p>

-----

- Reset Device:<br>
You can reset the device if you want to return to the original icons.<br><br>Please note this also resets the PIN code to <code>0000</code> and disable the secure boot.

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Reset.png">
</p>

<br>

-----

<br>

<h1 align="center">Build:</h1><a id="build"></a>

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/IMG_20230907_140559.jpg" width="500">
</p>

First, you need a board, select the cheapest link for you:

<code>Lilygo (China warehouse)</code>
- <a href="https://www.lilygo.cc/products/t-display-s3?variant=42589373268149?bg_ref=fq0SZYWvzA">T-Display-S3 (Touch Soldered Version [H589])</a>

<code>Lilygo (Germany warehouse)</code>
- <a href="https://www.lilygo.cc/products/t-display-s3-de?variant=42896523788469?bg_ref=fq0SZYWvzA">T-Display-S3 (Touch Soldered Version [SFNH589])</a>

<code>Lilygo (US warehouse)</code>
- <a href="https://www.lilygo.cc/products/t-display-s3-us?variant=44029410345141?bg_ref=fq0SZYWvzA">T-Display-S3 (Touch Soldered Version [H589US])</a>

<code>Aliexpress</code>
- <a href="https://www.aliexpress.us/item/3256804741686185.html">T-Display-S3 (Touch Soldered Version)</a>

<br>

There are several methods to build Willy, you can build him in DIY ways, or buy a Willy shield.

> <details><summary><code>D.I.Y Shield</code></summary><ul>
>   <br>
>   <li>1x TF Shield: <br> - Lilygo : T-Display TF Shied (Female PIN Version [H610]) - https://www.lilygo.cc/products/t-display-tf-shied?variant=42729797025973<br>or<br> - Aliexpress : T-Display TF Shied (Female PIN Version) - https://www.aliexpress.us/item/3256804956138540.html </li>
>   <br>
>   <li>1x CC1101 V2.0 Module: <br> - Aliexpress : https://www.aliexpress.us/item/2251832873028557.html </li>
>   <br>
>   <li>1x Infrared Receiver TSOP4838 ( or any IR receiver model with same specs ): <br> - Aliexpress : https://www.aliexpress.us/item/1005004481948853.html </li>
>   <br>
>   <li>1x Infrared LED TSAL6400 ( or any IR LED model with same specs ): <br> - Aliexpress : https://www.aliexpress.us/item/32670031000.html </li>
>   <br>
>   <li>1x Transistor 2N4401 ( or any transistor model with same specs )(Optional): <br> - Aliexpress : https://www.aliexpress.us/item/1005005484591463.html </li>
>   <br>
>   <br> <p align="center"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Diagram.png"> </p>
>   <li>Contact me on discord for more information</li>
> </ul></details>

> <details><summary><code>Willy Shield</code></summary><ul>
>   <br>
>   <li>Custom PCB soldered at the factory</li>
>   <li>Contact me on discord for more information</li>
>   <br> <p align="center"> <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Shield.png" width="500" height="311"> </p>
> </ul></details>

<br>

-----

<br>

<h1 align="center">Contact:</h1><a id="contact"></a>

<p align="center">
  <img src="https://raw.githubusercontent.com/h-RAT/Willy_Firmware_CC1101/main/Image/Discord.png" width="100" height="100"> 
  <br>
  <code>h_rat</code>
</p>

<h4 align="center">Website: https://willy-firmware.com/</h4>

<br>

-----

<br>

<h1 align="center">Disclaimer:</h1><a id="disclaimer"></a>

This device designed specifically for educational purposes. this device have been carefully developed to offer a hands-on experience in the field of cybersecurity and penetration testing. As a responsible provider, I would like to emphasize that any illegal use of this device is strictly prohibited.

It is crucial to acknowledge that using this device for any unauthorized activities, such as hacking or attempting to access sensitive information without proper authorization, is deemed illegal and unethical. I strongly discourage engaging in any activities that may cause harm, compromise security, or infringe upon others' privacy rights.

By accessing and utilizing this device, users take complete responsibility for their actions and the consequences that may arise from them. I expect users to act responsibly, adhere to ethical guidelines, and ensure that their activities remain within the boundaries of the law and ethical norms.

Remember, this device are aimed at promoting knowledge, improving cybersecurity skills, and raising awareness about the potential vulnerabilities present in infrastructures. I encourage you to explore this device, learn from them, and embrace the opportunity to enhance your understanding in a controlled and legal environment.

Thank you for your cooperation and commitment to responsible usage. Together, let us foster a secure and ethical cyberspace.
