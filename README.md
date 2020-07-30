# SmartSpaceBucket
Indoor Agriculture via MQTT, ESP01, ESP8266, ESP32, Sprouts, Grow-band LEDs

<img src="https://github.com/connerkward/SmartSpaceBucket/blob/master/Screen%20Shot%202020-07-30%20at%202.46.47%20PM.png" height="200"><img src="https://github.com/connerkward/SmartSpaceBucket/blob/master/Screen%20Shot%202020-07-30%20at%202.36.29%20PM.png" height="200"><img src="https://github.com/connerkward/SmartSpaceBucket/blob/master/Screen%20Shot%202020-07-30%20at%202.39.56%20PM.png" height="200"><img src="https://github.com/connerkward/SmartSpaceBucket/blob/master/Screen%20Shot%202020-07-30%20at%202.41.00%20PM.png" height="200">

<img src="https://github.com/connerkward/SmartSpaceBucket/blob/master/Screen%20Shot%202020-07-30%20at%203.01.01%20PM.png" height="200">


First iteration will be based on this micrgreen sprouter:

https://www.amazon.com/Deluxe-Kitchen-Sprouter-VICTORIO-VKP1200/

The original sprouter requires 2-3 waters a day, and each time unloading the leftover water at the bottom. Not great for busy folk!

I wanted to maintain lots of orginal parts on the sprouter because they are dishwasher safe, which 3d prints generally are not (and are also generally not food safe). Therefore in the design no contact between the prints and your sprouts ever occurs!

Included are an attachment for the top reservoir of the sprouter, and a replacemnet for the bottom level of the sprouter. The top attachment holds standard 1/4" OD tubing*, as does the new bottom, to facilate automatic drainage. 

Connect with a tank, pump and timer, your're off to the races. 
Smart version to be released for esp32 and mqtt home automation systems.

I have considered also desining a gravity fed version that uses some sort of gate or solenoid, but that would require lots of heavy water high up.


In future will develop grow system into fully contained bucket.

REQUIRE
- Mqtt broker machine, preferably server like RasPi, always online.
- MQTT tx/rx microcontroller(s), any board that is ESP32 based.
- some sensors
- a space bucket 

Design for bucket will follow.

*Designed for 6mm (possibly) and 1/4 inch OD tubing. Preferably food safe polyethelyne tubing.

If horticulturalists have ideas on how to use the water (distilled) that has been run through the sprouts, PM! 

What I would really like is a system that is easily expandable, clean (hence the dishwasher safe food-touching bits), and easily distributed. 
