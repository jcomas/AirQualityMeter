AIR QUALITY METER
=================


Goals:
-----
* DIY (you can modify it and improve it)
* Low cost equipment
* Easy and cheap replace of sensors
* Comprehensible air quality level indicator (good-green, fair-yellow, bad-red)
* History records
* Graphics


Hardware (first version):
------------------------
* [M5Stack Core2 ESP32 IoT Development Kit](https://docs.m5stack.com/#/en/core/core2?id=m5core2)
* [TVOC/eCO2 Gas Sensor Unit (SGP30)](https://docs.m5stack.com/#/en/unit/tvoc?id=tvoceco2)
* [ENV II Unit with Temperature Humidity Environment Sensor (SHT30+BMP280)](https://docs.m5stack.com/#/en/unit/envII?id=env-ii)


Software to compile: 
-------------------
[Visual Studio Code](https://code.visualstudio.com/) + [PlatformIO](https://platformio.org/install/ide?install=vscode) (arduino libraries, ESP32 SDK) 


Progress:
--------
* Publish first version
* Realtime data in text mode [done]
* Webserver [done]
* JSON output [done]
* Save history records
* New: Add LVGL library to improve interface (GUI)
* New: Include history graphics
* New: MQTT integration
* New: Home Assistant integration


Resources:
---------
* [IAQ Rating Index](http://www.iaquk.org.uk/ESW/Files/IAQ_Rating_Index.pdf) (english)
* [Aireamos project](https://www.aireamos.org/) (spanish)
* [Guía para ventilación de las aulas CSIC](https://digital.csic.es/handle/10261/221538) (spanish)
* [Cómo ventilar las aulas pasando menos frío. Aulas como espacios saludables](https://www.youtube.com/watch?v=1XhTSbLFt1w) (spanish)
