# Regional air quality forecasts at major European cities

This sample dataset contains extracted hourly forecast of the main pollutants:
  - ozone (O3)
  - nitrogen dioxide (NO2)
  - sulphur dioxide (SO2)
  - carbon dioxide (CO)
  - particulate matter > 10 µm (PM10)
  - particulate matter > 2.5 µm (PM25)
  - air quality index (AQI)  
  
at almost 3000 locations all over Europe. All values are in kg/m3 except AQI which is dimensionless index in the range between 1 and 5.

The details about locations can be found in [this file](https://github.com/OpenDataHack2018/Available-Open-Data/blob/master/CAMS/regional/CAMS_WEB_LOCATIONS_V1.csv).

# Data format

  - Files contain air quality forecasts for N of main European cities
  - Drag and drop images (requires your Dropbox account be linked)
  
```sh
ID,Date,Time,AQI,O3,NO2,SO2,CO,PM10,PM25
ALXX0001,2018-05-10,00:00,1,65.79,2.01,1.10,152.63,9.23,8.69
ALXX0001,2018-05-10,01:00,1,67.77,1.89,1.01,151.53,9.63,9.04
ALXX0001,2018-05-10,02:00,1,66.07,1.81,0.90,150.62,9.94,9.30
```
