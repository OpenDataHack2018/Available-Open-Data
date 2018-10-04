# Regional air quality forecasts at major European cities

This sample dataset contains extracted hourly forecasts up to three days ahead of the main pollutants:

  - ozone (O3)
  - nitrogen dioxide (NO2)
  - sulphur dioxide (SO2)
  - carbon dioxide (CO)
  - particulate matter > 10 µm (PM10)
  - particulate matter > 2.5 µm (PM25)
  - air quality index (AQI)  
  
at almost 3000 locations all over Europe. 

All values are in µg/m3 except AQI which is dimensionless index in the range between 1 and 5 indicating the level of air quality (1 - best, 5 - worst)

The details about locations can be found in [this file](https://github.com/OpenDataHack2018/Available-Open-Data/blob/master/CAMS/regional/CAMS_WEB_LOCATIONS_V1.csv).

# Data location and file naming convention

Sample data covering period from Nov 2017 to May 2018 is available on the public FTP server:

[ftp://ftp.ecmwf.int/pub/macc/atmoshack]

Files are named as

```sh
CAMS_WEB_FORECAST_${YYYYMMDD}_D+${DPLUS}.csv.gz
```
where

YYYYMMDD - date on which a forecast was generated
DPLUS - forecast range in days;
(T0 = YYYY-MM-DD 00UTC)

D+0 files contain forecast steps T0+0h..T0+24h
D+1 files contain forecast steps T0+25h..T0+48h
D+2 files contain forecast steps T0+49h..T0+72h
D+3 files contain forecast steps T0+73..T0+96h

For example, file CAMS_WEB_FORECAST_20180101_D+1.csv.gz with contain forecasts valid from 2018-01-02 01:00 to 2018-01-03 00:00.

# Data format

  - Data is encoded in gzipped CSV files
  - Files contain air quality forecasts for ~3000 of major European cities
  - Times are expressed in UTC
  
```sh
ID,Date,Time,AQI,O3,NO2,SO2,CO,PM10,PM25
ALXX0001,2018-05-10,00:00,1,65.79,2.01,1.10,152.63,9.23,8.69
ALXX0001,2018-05-10,01:00,1,67.77,1.89,1.01,151.53,9.63,9.04
ALXX0001,2018-05-10,02:00,1,66.07,1.81,0.90,150.62,9.94,9.30
```

# Sample data extraction

See this Jupyter notebook:
https://github.com/OpenDataHack2018/Available-Open-Data/blob/master/Reading_CAMS_regional_data.ipynb
