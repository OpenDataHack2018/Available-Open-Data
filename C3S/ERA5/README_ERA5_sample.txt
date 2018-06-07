era5-sample-data_final_YYYY.csv contains 8 columns for more than 7,300 cities around the world.

1) city_id: City identifier used in the city definition file simplemaps-worldcities-basic-with-index.csv
2) month: YYYYMM
3) 10u: 10 metre U wind component, units: m/s
4) 10v: 10 metre V wind component, units: m/s
5) 2t: 2 metre temperature, units: K
6) msl: mean sea level pressure, units: Pa
7) tcc: total cloud cover, units: (0 - 1),
8) tp: total precipitation, units: m

The values of parameters 5-8 are monthly means of daily means processed from the C3S ERA5 dataset.

simplemaps-worldcities-basic-with-index.csv is the city definition file from https://simplemaps.com/data/world-cities, with index added as the first column. You will find latitude, longitude, population, country, etc. from the file.
