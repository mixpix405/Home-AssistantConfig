# Home-Assistant Config by [@mixpix405](http://www.twitter.com/mixpix405)
[Home Assistant](https://home-assistant.io/) configuration files (and some referenced files)

**This readme is really old... I'll update it eventually...

![Screenshot of all stuff in Home Assistant](https://imgur.com/QzSgzEZ.gif)

**Devices I'm using:**
* **Google WiFi** : My router. I like it. It works.
* **RaspberryPi 3**
* **Aeotec Z-Stick (Gen 5)** : To controll z-wave devices
* **Z-wave devices** :
    *   **4x GE z-wave in-wall switches**
    *   **2x [GoControl FS20Z-1](https://www.amazon.com/GoControl-Z-Wave-Isolated-Contact-Fixture/dp/B00ER6MH22)**: To control my garage doors
* **2x [Sonoff Basic](https://www.itead.cc/sonoff-wifi-wireless-switch.html)**: Using these as WiFi/MQTT-enabled extension cords. Great around Christmas time to automate the Christmas tree, etc. They've been flashed with the [Tasmota custom firmware](https://github.com/arendst/Sonoff-Tasmota) to enable MQTT funcationality, etc.
* **SmartThings Hub** : I currently have this talking to HA via MQTT. I've mostly migrated from ST to HA (all z-wave devices are controlled by HA, as are all automations), but I had a few zigbee devices that I'm still controlling / monitoring this way.
* **Zigbee Devices** : 
    * **[Visonic Open/Close Sensors](https://www.amazon.com/Visonic-MCT-340-Wireless-Window-Temperature/dp/B06XDJ3KYC)**: Using 2 of these to sense my garage doors' open/close state. Got them for cheap ($6 ea) on Black Friday
    * **PEQ Door Sensor** : This was cheap and works great. Reports open/close, as well as temperature. Unfortunately, I can't get their online store to load any longer, so... I can't buy any more.
    * **PEQ Motion Sensor** : Same as above, except detects motion (obviously) and temp.
    * **PEQ Dimmable Outlet** : Using this for a bedside lamp.
* **Google Home + 3x Google Home Minis** : These are great for all sorts of stuff, including TTS to scream at the family in the morning letting them know that they'll inevitably be late for school/work.
* **Nest Thermostat**

**Google Assistant Integration**
- Using this, I can talk to my Google Homes (or, Assistant on my Android phone) to say something like *"Hey, Google... Close Megan's garage door"*, and like magic, exactly that happens!

## More Screenshots:

![Landing Page](https://imgur.com/xtBjrus.png)
![Morning Announcements](https://imgur.com/MrkMrus.png)
![Network Devices](https://imgur.com/rAnmnE7.png)
![Climate Control](https://imgur.com/7q4RO0f.png)
![Automation](https://imgur.com/YJBqCNX.png)
![Media Players](https://imgur.com/xeyboYC.png)
![Device Trackers](https://imgur.com/4lgldWN.png)
![SmartThings Integration](https://imgur.com/jbkJdiX.png)
![Z-Wave Devices](https://imgur.com/SplXlbC.png)

## To Do:

- [x] Get z-wave integrated directly
- [x] Implement night mode theme, automated
- [x] Bring in automations from ST
- [x] Setup nmap for device tracking
- [x] Notify if close to SSL expiry
- [x] Get HTML5 push notifications working
- [x] Battery charging status for trackers
- [ ] Get rid of pointless stuff on front-end
- [x] Re-organize into fewer, more relevant tabs