# NAVDoctor

Welcome to our NAVDoctor GitHub site. This site is intended to be a central hub for all NAVDoctor users to access important updates, report any issues they have found or request new features.
<br>
<img src="https://github.com/digitalyacht/NAVDoctor/raw/main/Images/NavDoctor.jpg" width=70%>
<br>
The NAVDoctor wireless NMEA2000 Diagnostic Tool is designed to allow a marine installation engineer to test and diagnose NMEA 2000 networks.

NAVDoctor shares the same form factor and enclosure as our NavLink2 wireless NMEA 2000 gateway and takes its power from the NMEA 2000 network via its integral NMEA 2000 drop cable, which is terminated in the standard M12 male NMEA 2000 connector.

Once plugged in to a spare "T-Piece" on the NMEA 2000 network, NAVDoctor will create its own wireless network with an SSID (wireless network name) of **NavDoctor-xxxx** where xxxx is the last four digits of its MAC address. The wireless password is **PASS-xxxx** where xxxx is the same four digits as the SSID.

Once wirelessly connected, open a browser on your mobile device and you should be able to access the NAVDoctor's web interface at...

http://192.168.1.1   or   http://navdoctor.local

...which will display the home page as shown below.

<img src="https://github.com/digitalyacht/NAVDoctor/raw/main/Images/Home.png" width=70%>

For more information on using NAVDoctor please download the User Manual or watch the video below.

Included in this repository are:-

*1.  NAVDoctor Product Release Presentation (pdf)*

*2.  The latest NAVDoctor firmware (2.43)*

*3.  Latest User Manual for NAVDoctor (pdf)*

Below is a training video on how you can use the NAVDoctor to diagnose and test an NMEA 2000 network.

[![NAVDoctor Training Video](https://img.youtube.com/vi/0hp9t8hmCwI/0.jpg)](https://www.youtube.com/watch?v=0hp9t8hmCwI)

We are continuously updating NAVDoctor and below is the Firmware history...

v2.43 - Improved Help text plus couple of formatting improvements

v2.4 - PGN page popup: units converted to more conventional

v2.3 - New PGN 128780 added for Jack Plate, sending welcome text to tcp/udp

v2.2 - mDNS issue when on same network as NavLink2

v2.1 - OTA firmware update function improved

v2.0 - fixing Gateway firmware version display

v1.9 - Displaying its own IP address on Settings page

v1.8 - Proprietary PGN support

v1.6 - introducing signed int to display negative values on PGN page popup window

v1.5 - Device List updated. Every 2 seconds checks NSM to see if number of devices are the same as number of lines in device list. Makes a request to STM32 for NAME`s if not. Instance field also improved.
