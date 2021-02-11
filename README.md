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
* Readings each 1 or 2 minutes for battery powered devices.
* Calibration according to manufacturer CO2 sensor (minimum 20 minutes outdoors, avoid to be near persons, vehicles and other contaminants)
* Lifetime of NDIR CO2 sensors: 5, 10 or 15 years.
  
  
Other projects:
--------------
* [Codos](https://github.com/miguelangelcasanova/codos)
* [Anaire](https://github.com/anaireorg/anaire-devices) 
* [eMariete](https://emariete.com/en/home-co2-meter/)
* [TTNMAD CO2 Free](https://github.com/IoTopenTech/TTNMAD_CO2_FREE) [& this](https://www.medialab-prado.es/en/activities/building-co2-nodes-lorawan-and-ttnmad-v23)
* [co2meter](https://github.com/miguelfreitas/co2meter) 
* [Medición de CO2](http://www.jorgealiaga.com.ar/?page_id=2864)
* [M5Stack ESP32 Core Ink + SCD30](https://github.com/hpsaturn/co2_m5coreink)
* [CanAirIO Citizen network for monitoring air quality](https://canair.io/)
* [Medidor CO2 DYI. WemosD1-Wifi. Sensor NDIR. Oled. HA](https://www.youtube.com/watch?v=Gk2qnFJ18o8&feature=youtu.be)
* [Air Particules Monitor](https://sensor.community/en/sensors/airrohr/)

  
Resources:
---------
* [IAQ Rating Index](http://www.iaquk.org.uk/ESW/Files/IAQ_Rating_Index.pdf) (english)
* [Aireamos project](https://www.aireamos.org/) (spanish)
* [Guía para ventilación de las aulas CSIC](https://digital.csic.es/handle/10261/221538) (spanish)
* [Cómo ventilar las aulas pasando menos frío. Aulas como espacios saludables](https://www.youtube.com/watch?v=1XhTSbLFt1w) (spanish)
* [CanAirIO Air Quality Sensors Library](https://github.com/kike-canaries/canairio_sensorlib)


Commercial products:
-------------------
* Aranet 4 [(spanish info)](https://www.aranet4.es/) [(english info)](https://aranet4.com/) [(teardown)](https://kaspars.net/blog/aranet4-teardown)  
  NDIR sensor: SenseAir Sunrise
* Carbon Dioxide Detector EM002 [(manufacturer)](https://www.alibaba.com/product-detail/Portable-Digital-Co2-Meter-Co2-Monitor_1600141548089.html?spm=a2700.shop_index.111720.3.ad642356fgKz1j) [(reseller)](https://www.kkmoon.com/p-e9194.html)  
  NDIR sensor: Honeywell CRIR M1 / SenseAir S8
* Temp. RH CO2 Meter 7755 AZ [(info)](https://www.az-instrument.com.tw/en/product-616380/Temp-RH-CO2-Meter-7755-AZ.html)
* Temtop M2000 Air Quality Monitor [(info)](https://www.elitechustore.com/collections/air-quality-detector/products/temtop-m2000-2nd-generation-air-quality-monitor-for-pm2-5-pm10-particles-co2-hcho-temperature-humidity-settable-audio-alarm-data-export-recording-curve-easy-calibration) [(video)](https://www.youtube.com/watch?v=ITUzYioZhCs)
