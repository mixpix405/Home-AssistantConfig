# Home-Assistant Config by [@mixpix405](http://www.twitter.com/mixpix405)
[Home Assistant](https://home-assistant.io/) configuration files (and some referenced files)

This is the initial commit. Everything is pretty poorly organized, but it works. I'll be getting it all organized better as I go along.

![Screenshot of all stuff in Home Assistant](https://imgur.com/zBFvAal.png)

**Devices I'm using:**
* **Google WiFi** : My router. I like it. It works.
* **SmartThings Hub** : I currently have this talking to HA via MQTT. I will be getting rid of this and getting a z-wave USB stick for the Pi so that it's all self-contained. But, it's working for now this way, so...
* **Google Home + Google Home Mini** : These are great for all sorts of stuff, including TTS to scream at the family in the morning letting them know that they'll inevitably be late for school/work.
* **Nest Thermostat**
* **Z-Wave Devices** :
    * **PEQ Door Sensor** : This was cheap and works great. Reports open/close, as well as temperature. Unfortunately, I can't get their online store to load any longer, so... I can't buy any more.
    * **PEQ Motion Sensor** : Same as above, except detects motion (obviously) and temp.
    * **PEQ Dimmable Outlet** : Using this for a bedside lamp.
    * **Several GE z-wave wall switches** : Again, currently these are going thru SmartThings to HA via MQTT. Next step is to connect them directly to HA via the aforementioned usb z-wave stick.

## More Screenshots:
![Morning Announcements](https://imgur.com/6ZJI1DZ.png)
![Network Devices](https://imgur.com/NJOJuKL.png)
![Climate Control](https://imgur.com/SJ7egNa.png)
![Automation](https://imgur.com/dDxp56F.png)
![Media Players](https://imgur.com/ejFWicA.png)
![Device Trackers](https://imgur.com/ASVyYXT.png)
![SmartThings Integration](https://imgur.com/FuxL6Zk.png)