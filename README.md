# SmartSpaceBucket
<img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/connerkward/SmartSpaceBucket"> <img alt="GitHub" src="https://img.shields.io/github/license/connerkward/SmartSpaceBucket"> <img alt="GitHub issues" src="https://img.shields.io/github/issues-raw/connerkward/SmartSpaceBucket"> <img alt="GitHub followers" src="https://img.shields.io/github/followers/connerkward?label=Follow&style=social"><br/>

Distributable Indoor Agriculture via MQTT, ESP01, ESP8266, ESP32, Grow-band LEDs

<img src="https://github.com/connerkward/SmartSpaceBucket/blob/master/screenshots/multi_function_display.png" height="200"><img src="https://github.com/connerkward/SmartSpaceBucket/blob/master/screenshots/web_stackable_doser.png" height="200"><img src="https://github.com/connerkward/SmartSpaceBucket/blob/master/screenshots/grow_computer.png" height="200">

<!---
<img src="https://github.com/connerkward/SmartSpaceBucket/blob/master/Screen%20Shot%202020-07-30%20at%203.01.01%20PM.png" height="200">
-->

<h4>ITERATION 1.0 ~ SPROUTER [COMPLETED]</h4>

First iteration is based on this microgreen [Sprouter](https://www.amazon.com/Deluxe-Kitchen-Sprouter-VICTORIO-VKP1200/dp/B01AJJOJD0/ref=sxts_sxwds-bia-wc-p13n1_0?cv_ct_cx=sprouter&dchild=1&keywords=sprouter&pd_rd_i=B01AJJOJD0&pd_rd_r=98c6fbe5-43cb-46d2-b28d-60167a19037d&pd_rd_w=0nLz4&pd_rd_wg=CAVLj&pf_rd_p=13bf9bc7-d68d-44c3-9d2e-647020f56802&pf_rd_r=NT4WZ26WTYZBTFNQ22DW&psc=1&qid=1596146741&sr=1-1-791c2399-d602-4248-afbb-8a79de2d236f)

The original sprouter requires 2-3 waters a day, and each time unloading the leftover water at the bottom. Not great for busy folk! We wanted to maintain lots of orginal parts on the sprouter because they are dishwasher safe, which 3d prints generally are not (and are also generally not food safe). Therefore in the design no contact between the prints and your sprouts ever occurs!

Included are an attachment for the top reservoir of the sprouter, and a replacement for the bottom level of the sprouter. The top attachment holds standard 1/4" OD tubing*, as does the new bottom, to facilate automatic drainage. 

[Sprouter] + [3D printed Drain] + [web_valve bot] or [pump bot and reservoir] = Hassle free sprouts.

<h4>ITERATION 2.0 ~ SPACE BUCKET [IN PROGRESS]</h4>
Fully contained grow computer, with optional soil moisture probes and temprature probes, optional pump I2C out, and a web interface, running on an ESP32/ESP8266/ESP01. Integrated fan control to regulate temperature. Current design uses off the shelf pc fan and off the shelf pcie usb adapter for a plug and play experience of sensors, pump interfaces, and fan interfaces.<br/>

  - CAD GROW COMPUTER **[COMPLETE]**
  - CIRCUIT DIAGRAM GROW COMPUTER (5V Only USB Ports)
  - CAD BUCKET ADAPTER PLATES **[COMPLETE]**
  - INO GROW COMPUTER
  
<h4>ITERATION 3.0 ~ INTEGRATED HYDROPONICS [PLANNING]</h4>
A dockerized server, uses MQTT to send timed alerts to dosage bot (accurately doses hydroponic nutrients), stir bot (vitally agitates nutrient solution) and bucket/pump controller (pumps mixed nutrient solution from resevoir to plants), as well as provides a web interface for entire system and sensors.

*Designed for 6mm (possibly) and 1/4 inch OD tubing. Preferably food safe polyethelyne tubing.
If horticulturalists have ideas on how to reuse the water that has been run through the sprouts, PM
