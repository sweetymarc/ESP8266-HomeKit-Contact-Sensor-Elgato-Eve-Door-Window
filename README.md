# ESP8266  HomeKit Contact Sensor Elgato Eve Door Window
ESP8266 based  HomeKit Contact Sensor that works like Elgato Eve Door &amp; Window using Wi-fi


------
[![Instagram URL](https://img.shields.io/twitter/url/https/www.instagram.com/homekidd?label=Follow&logo=instagram&style=social)](https://www.instagram.com/homekidd) [![FaceBook URL](https://img.shields.io/twitter/url/https/www.facebook.com/HomeKiid?label=Like&logo=facebook&style=social)](https://www.facebook.com/HomeKiid) [![YouTube URL](https://img.shields.io/twitter/url/https/www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA?label=Follow&logo=youtube&style=social)](https://www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA)
------

[![GitHub All Releases](https://img.shields.io/github/downloads/HomeKidd/ESP8266-HomeKit-Contact-Sensor-Elgato-Eve-Door-Window/total?color=green)](https://github.com/HomeKidd/ESP8266-HomeKit-Contact-Sensor-Elgato-Eve-Door-Window/releases) 
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/HomeKidd/ESP8266-HomeKit-Contact-Sensor-Elgato-Eve-Door-Window?color=yellow&label=Latest%20Release)](https://github.com/HomeKidd/ESP8266-HomeKit-Contact-Sensor-Elgato-Eve-Door-Window/releases) 
[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CEYEK69ZYG69S&source=url)
<br/>
<br/>


For **Usage** please read the [Build Instructions](https://github.com/HomeKidd/ESP8266-HomeKit-Contact-Sensor-Elgato-Eve-Door-Window/wiki/Build-Instructions) Wiki page!<br/><br/>


**This HomeKit enabled sensor works the same as [Elgato EVE Door & Window](https://www.evehome.com/en/eve-door-window)!** 



**Features:**
* Door State _(via a simple [Door Sensor](http://s.click.aliexpress.com/e/CtE47VyU))_
* Times Opened counting _(only in Elgato Eve app)_
* Last Motion displaying _(only in Elgato Eve app, not working yet)_
* Opened / Closed Duration displaying _(only in Elgato Eve app, not working yet)_
* Reset Times Opened value to 0 _(only in Elgato Eve app)_
* Reset button
* Over-the-Air firmware update _(still beta)_
* ~~Data history~~ (not working, not reliable enough)

**GPIO12 used for the sensor**
 
<br/>
<br/>
<img src="https://github.com/HomeKidd/ESP8266-HomeKit-Motion-Sensor-Elgato-Eve/raw/master/images/homekid_motion.jpg" class="center" width="450"/>

<br/>

**Demo:**

<br/>
<img src="https://github.com/HomeKidd/ESP8266-HomeKit-Motion-Sensor-Elgato-Eve/raw/master/images/homekid_motion.png" class="center" width="450"/>

<br/>
<br/>

This project uses the Apple HomeKit accessory server library [ESP-HomeKit](https://github.com/maximkulkin/esp-homekit) from [@MaximKulkin](https://github.com/maximkulkin) for [ESP-OPEN-RTOS](https://github.com/SuperHouse/esp-open-rtos).<br/>

Although already forbidden by the sources and subsequent licensing, it is not allowed to use or distribute this software for a commercial purpose.<br/><br/>

<img src="https://freepngimg.com/thumb/apple_logo/25366-7-apple-logo-file.png" width="20"/> 

###### HomeKit Accessory Protocol (HAP) is Apple’s proprietary protocol that enables third-party accessories in the home (e.g., lights, thermostats and door locks) and Apple products to communicate with each other. HAP supports two transports, IP and Bluetooth LE. The information provided in the HomeKit Accessory Protocol Specification (Non-Commercial Version) describes how to implement HAP in an accessory that you create for non-commercial use and that will not be distributed or sold.

###### The HomeKit Accessory Protocol Specification (Non-Commercial Version) can be downloaded from the [HomeKit Apple Developer page.](https://developer.apple.com/homekit/)

###### Copyright © 2019 Apple Inc. All rights reserved.
