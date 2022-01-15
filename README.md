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
  
  
Easy projects:
-------------
* [Aireamos Makers](https://www.aireamos.org/aireamos-makers/)

  
Other projects:
--------------
* [eMariete - several CO2 projects](https://emariete.com/en/) [(CO2 Easy Meter)](https://emariete.com/en/diy-co2-monitor-wifi/)  [(Gadget CO2 Meter)](https://emariete.com/en/meter-co2-gadget/)  [(FAQ problemas del Medidor de CO2 con ESP Easy)](https://emariete.com/medidor-casero-co2/#_Tienes_problemas_Preguntas_mas_frecuentes_del_medidor_de_CO2)
* [CanAirIO Citizen network for monitoring air quality](https://canair.io/)
* [Codos](https://github.com/miguelangelcasanova/codos)
* [Anaire](https://github.com/anaireorg/anaire-devices) 
* [TTNMAD CO2 Free](https://github.com/IoTopenTech/TTNMAD_CO2_FREE) [& this](https://www.medialab-prado.es/en/activities/building-co2-nodes-lorawan-and-ttnmad-v23)
* [co2meter](https://github.com/miguelfreitas/co2meter) 
* [Medición de CO2](http://www.jorgealiaga.com.ar/?page_id=2864)
* [M5Stack ESP32 Core Ink + SCD30](https://github.com/hpsaturn/co2_m5coreink)
* [Medidor CO2 DYI. WemosD1-Wifi. Sensor NDIR. Oled. HA](https://www.youtube.com/watch?v=Gk2qnFJ18o8&feature=youtu.be)
* [Air Particules Monitor](https://sensor.community/en/sensors/airrohr/)
* [Monitoring CO2 using APP (LILYGO TTGO T-Display ESP32 + Bluetooth (includes Sensirion APP) + Sensirion SCD30 CO2)](https://github.com/Sensirion/arduino-ble-gadget/blob/master/documents/SCD30_Monitor_Tutorial.md)
* [LibreCO2](https://github.com/danielbernalb/LibreCO2)
* [CO2 Watch](https://emariete.com/en/hairpiece2-meter-co2-wrist-wearable/)
* [Zigbee + CO2 sensor](https://github.com/diyruz/AirSense)
* [Wemos D1 Mini + SCD30 + Thingsboard + Telegram](https://github.com/Alitux/solarco2)
* [Upload your CO2 data to public server and see on map](https://covid-co2-tracker.herokuapp.com/home)
* Projects using traffic lights: [Project 1](https://github.com/dennisheitmann/CO2-Ampel), [Project 2](https://github.com/Eisbaeeer/CO2light)
* Power plug model: [Components](http://pits.tgd-consulting.de/#Komponenten), [source code](https://github.com/TGD-Consulting/PiTS-ESP8226), [3D model](https://cults3d.com/en/3d-model/gadget/co2-light-ring), [assembly](https://forum-raspberrypi.de/forum/thread/49535-guenstige-co2-ampel-im-eigenbau/?postID=488016#post488016), [schematic](https://forum-raspberrypi.de/forum/thread/49535-guenstige-co2-ampel-im-eigenbau/?postID=454325#post454325)
* [DIY ESP Easy CO2 Device](https://www.laboiteaformes.fr/acheter-capteur-de-co2/)
* [French makers](https://nousaerons.fr/makersco2/)
* [Medidor de CO2](https://github.com/droyktton/medidorCO2)
* [Sensor de CO2 para colegios](https://www.medialab-uniovi.es/pro-sensorco2.php)

Icons:
-----
* [Cupertino Truetype Font (icons)](https://github.com/flutter/cupertino_icons/blob/master/assets/CupertinoIcons.ttf)
* [Font Converter (to use TTF o WOFF truetype icons in your C code, supports LVGL)](https://lvgl.io/tools/fontconverter)
* [truetype2gfx (to convert fonts to Adafruit GFX, you move icons to begin of TrueType font using FontForge)](https://rop.nl/truetype2gfx/)
* [FontForge (font editor)](https://fontforge.org/en-US/)


Resources:
---------
* [Daily global CO2](https://www.esrl.noaa.gov/gmd/ccgg/trends/gl_trend.html)
* [Carbon dioxide forecasts](https://atmosphere.copernicus.eu/charts/cams/carbon-dioxide-forecasts?facets=undefined&time=2021091900,3,2021091903&projection=classical_global&layer_name=composition_co2_surface)
* [IAQ Rating Index](http://www.iaquk.org.uk/ESW/Files/IAQ_Rating_Index.pdf) (english)
* [Aireamos project](https://www.aireamos.org/) (spanish)
* [Guía para ventilación de las aulas CSIC](https://digital.csic.es/handle/10261/221538) (spanish)
* [Cómo ventilar las aulas pasando menos frío. Aulas como espacios saludables](https://www.youtube.com/watch?v=1XhTSbLFt1w) (spanish)
* [CanAirIO Air Quality Sensors Library](https://github.com/kike-canaries/canairio_sensorlib)
* [CO2 expelled by a person seen from a thermal camera](https://amp.rtve.es/noticias/20210312/coronavirus-aerosoles-imagenes/2081740.shtml) (spanish)
* [Improving Indoor Air Quality in California Schools](https://wcec.ucdavis.edu/improving-indoor-air-quality-in-california-schools/)
* [Calculadora de CO2](https://droyktton.github.io/loscoihues/ventilacion/CO2ACHProbInfeccionV3.html)
* [CO2 French Working Group](https://projetco2.fr/)

Commercial products:
-------------------
* Comparative table of commercial products [(japanese)](https://covidco2jp.wordpress.com/2021/01/17/co2/)
* [Teardown of several CO2 meters](https://wiki.liutyi.info/display/CO2/Monitors)
* Aranet 4 [(spanish info)](https://www.aranet4.es/) [(english info)](https://aranet4.com/) [(teardown)](https://kaspars.net/blog/aranet4-teardown) [(forum)](https://forum.aranet.com/)   
  NDIR sensor: SenseAir Sunrise
* CO2Panel PI [(spanish info)](https://co2panel.shop/products/co2panel-pi-medidor-co2-para-colegios-de-bajo-coste-led-informativo-y-conexion-a-internet)  
* Carbon Dioxide Detector EM002 [(manufacturer)](https://gd-deyi.en.alibaba.com/product/1600208803526-819921884/DEYI_Indoor_CO2_Meter_Temperature_and_Relative_Humidity_Carbon_Dioxide_Detector_NDIR_Channel_Sensor_Data_Logger_0_9999ppm.html) [(reseller)](https://www.kkmoon.com/p-e9194.html) [(interactive guide in spanish)](https://view.genial.ly/5fda916d37663f0d6c04ee89)  
  NDIR sensor: Honeywell CRIR M1 / SenseAir S8 / Cubic CM1106 / ZyAura ZG09
* Dienmern DM306C [(manufacturer)](http://www.langder.com/productshow.asp?showidd=74&ClassID2=) [(distributor)](https://www.alibaba.com/product-detail/Carbon-Dioxide-Detector-CO2-Detector-Dienmern_1600147388764.html)  
  NDIR sensor: Winsen
* Temp. RH CO2 Meter 7755 AZ [(info)](https://www.az-instrument.com.tw/en/product-616380/Temp-RH-CO2-Meter-7755-AZ.html)
* Temtop M2000 Air Quality Monitor [(info)](https://www.elitechustore.com/collections/air-quality-detector/products/temtop-m2000-2nd-generation-air-quality-monitor-for-pm2-5-pm10-particles-co2-hcho-temperature-humidity-settable-audio-alarm-data-export-recording-curve-easy-calibration) [(video)](https://www.youtube.com/watch?v=ITUzYioZhCs)
* Netatmo [(teardown)](https://www.fictiv.com/teardowns/netatmo-weather-station-teardown-part-2-indoor-module)
