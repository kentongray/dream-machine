# The Homer


[![The Homer for a modern age](https://img.youtube.com/vi/Pw9gaEiQAxY/0.jpg)](https://www.youtube.com/watch?v=Pw9gaEiQAxY)

Python3/Raspberry Pi project to control my house (nest, hue and chromecast audio, and stereo system) quickly (REAL BUTTONS!) from the comfort of my bed.

this is a pet project and probably not of use to anyone but happy to help anyone looking for some help, open up an issue or on twitter @kentonue

## Config
 Create a config.py and add the following
 ```
 nest_username = "you@domain.com"
 nest_password = "supersecurepassword"
 ```
## Current Features
 * On/Off Hue Lights via GPIO button
 * Play/Pause Chromecast
 * Dimmer control via potentiometer and MCP3008
 * [IR remote Support](https://www.amazon.com/HX1838-Infrared-Wireless-Control-Arduino/dp/B019I4MYSE/ref=sr_1_8?ie=UTF8&qid=1484505577&sr=8-8&keywords=ir+remote+and+sensor) ("standard" NEC, native no lirc!) 
 * Broadlink IR Blaster Support
 * Mobile Web UI
 
 
## Wish List
 * Notification Center App
 * Display Support
 * Random use of my other sensors
 * Convert to rust?!
 
Schematic in the fritzing folder
<img width="647" alt="board" src="https://cloud.githubusercontent.com/assets/100857/21959727/3f92c2bc-da96-11e6-9e0b-b19ca22ed45d.png">
![schematic](https://cloud.githubusercontent.com/assets/100857/21959730/59413022-da96-11e6-9783-85f8000bdc65.png)
