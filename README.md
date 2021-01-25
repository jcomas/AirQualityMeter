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
* Portable (battery included)


Hardware (first version):
------------------------
* [M5Stack Core2 ESP32 IoT Development Kit](https://docs.m5stack.com/#/en/core/core2?id=m5core2)
* [TVOC/eCO2 Gas Sensor Unit (SGP30)](https://docs.m5stack.com/#/en/unit/tvoc?id=tvoceco2)
* Temperature, humidity & barometric pressure sensors: [ENV II Unit with Temperature Humidity Environment Sensor (SHT30+BMP280)](https://docs.m5stack.com/#/en/unit/envII?id=env-ii)
* NDIR CO2 Sensors: Sensirion SCD30, SenseAir Sunrise


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


Considerations for CO2 Sensor:
-----------------------------
* Readings each 1 or 2 minutes.
* Calibration according to manufacturer CO2 sensor.
* Lifetime of NDIR CO2 sensors: 5, 10 or 15 years.


Other projects:
--------------
* [Codos](https://github.com/miguelangelcasanova/codos)
* [Anaire](https://github.com/anaireorg/anaire-devices) 
* [eMariete](https://emariete.com/en/home-co2-meter/)
* [TTNMAD CO2 Free](https://github.com/IoTopenTech/TTNMAD_CO2_FREE) [& this](https://www.medialab-prado.es/en/activities/building-co2-nodes-lorawan-and-ttnmad-v23)
* [co2meter](https://github.com/miguelfreitas/co2meter) 


Resources:
---------
* [IAQ Rating Index](http://www.iaquk.org.uk/ESW/Files/IAQ_Rating_Index.pdf) (english)
* [Aireamos project](https://www.aireamos.org/) (spanish)
* [Guía para ventilación de las aulas CSIC](https://digital.csic.es/handle/10261/221538) (spanish)
* [Cómo ventilar las aulas pasando menos frío. Aulas como espacios saludables](https://www.youtube.com/watch?v=1XhTSbLFt1w) (spanish)
* [CanAirIO Air Quality Sensors Library](https://github.com/kike-canaries/canairio_sensorlib)


Commercial products:
-------------------
* Aranet 4 [(spanish)](https://www.aranet4.es/) [(english)](https://aranet4.com/)
