# Home-Assistant Config by [@mixpix405](http://www.twitter.com/mixpix405)
[Home Assistant](https://home-assistant.io/) configuration files (and some referenced files)

![Screenshot of all stuff in Home Assistant](https://imgur.com/QzSgzEZ.gif)

**Devices I'm using:**
* **Google WiFi** : My router. I like it. It works.
* **RaspberryPi 3**
* **Aeotec Z-Stick (Gen 5)** : To controll z-wave devices!
* **Z-wave devices** : 4 GE z-wave in-wall switches
* **SmartThings Hub** : I currently have this talking to HA via MQTT. I've mostly migrated from ST to HA (all z-wave devices are controlled by HA, as are all automations), but I had a few zigbee devices that I'm still controlling / monitoring this way.
* **Zigbee Devices** : 
    * **PEQ Door Sensor** : This was cheap and works great. Reports open/close, as well as temperature. Unfortunately, I can't get their online store to load any longer, so... I can't buy any more.
    * **PEQ Motion Sensor** : Same as above, except detects motion (obviously) and temp.
    * **PEQ Dimmable Outlet** : Using this for a bedside lamp.
* **Google Home + Google Home Mini** : These are great for all sorts of stuff, including TTS to scream at the family in the morning letting them know that they'll inevitably be late for school/work.
* **Nest Thermostat**

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
- [ ] Notify if close to SSL expiry
- [x] Get HTML5 push notifications working
- [x] Battery charging status for trackers
- [ ] Get rid of pointless stuff on front-end
- [ ] Re-organize into fewer, more relevant tabs