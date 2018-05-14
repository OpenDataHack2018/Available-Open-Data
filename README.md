# Available-Open-Data

<h1>From the ECMWF Copernicus Climate Change Service (C3S)</H1>

<h3>ERA5 - Global Climate Reanalysis data (2008-present available now)</h3>
<ul>
<li><a href="https://software.ecmwf.int/wiki/display/CKB/What+is+ERA5">What is ERA5</a>
<li><a href="https://software.ecmwf.int/wiki/display/CKB/ERA5+data+documentation">ERA5 documentation</a>
<li>Download ERA5 data via the Climate Data Store
<li>ERA5 data Samples available <a href="ftp://ftp.ecmwf.int/pub/copsup/">here</a>
</ul>

<!--
<h3>Seasonal Forecasts</H3>
<ul>
<li><a href="http://climate.copernicus.eu/s/charts/c3s_seasonal/">Charts</a> including: MSLP charts, SST maps and NINO-index timeseries, 2m Temperature charts, 850mb Temperature charts, Geopotential height at 500Pa  charts, Precipitation charts. The forecasts are updated every month and cover a time range of 6 months.
<li>Archived data in the Climate Data Store
<li>Seasonal forecast data Samples available <a href="ftp://ftp.ecmwf.int/pub/copsup/">here</a>
</ul>        
-->

<h3>Data from the Sectoral Information System (SIS)</h3>
<ul>
<li>WATER Sector: End-to-end Demonstrator for improved decision making in the water sector in Europe (EDgE) and Service for Water Indicators in Climate Change Adaption (SWICCA)
<li>ENERGY Sector: European Climatic Energy Mixes (ECEM) and CLIM4ENERGY
<li>INSURANCE Sector: Wind Storm Climate Service (WISC)
</ul>

<h3>Monthly State of Climate (Maps):</h3>
<ul>
  <li>Average surface air temperature monthly maps:
        Latest monthly map
        Archived maps from August 2015.
    <li>Monthly sea-ice maps:
        Latest Monthly Maps
        Archived maps from March 2017.
    <li>Monthly summaries of precipitation, relative humidity and soil moisture:
        Latest Monthly Maps
        Archived maps from April 2017
 </ul>       

<h3>Essential Climate Variables (ECVs) - Soon available through the CDS</h3>

    Sea ice concentration, sea ice edge and type, sea ice thickness
    Sea level
    Sea surface temperature (SST)
    Ozone
    Total column and vertical aerosol information
    Carbon dioxide and methane
    Soil moisture
    Glaciers and ice caps
    Surface albedo, leaf area index (LAI) and the fraction of absorbed photosynthetic active radiation (FAPAR)



<h1>From the ECMWF Copernicus Atmosphere Monitoring Service (CAMS)</H1>

<h3>Global CAMS data:</h3>

<ul>    
  <li>Latest three days of Real-Time CAMS global daily analysis and forecast data are available through the FTP Dissemination server.
    <li>CAMS Global archived analysis and forecast daily data (6 hourly analysis and 3 hourly up-to 5 days forecast data since 05/07/2012, available with a 5-day delay, approximately 40km horizontal resolution (T511 spectral) on 60 vertical levels from the surface up to 0.1 hPa, are available for download through:
        <ul>
        <li>the ECMWF data server web interface: http://apps.ecmwf.int/datasets/data/cams-nrealtime/levtype=sfc/ , one month at a time
        <li>WebAPI, allowing users to download Global CAMS data in a programmatic way (using Python - example scripts are available)
</ul>
    <li>CAMS Global archived reanalysis data (MACC Reanalysis - 2003-2012, approximately 80 km (T255 spectral) on 60 vertical levels from the surface up to 0.1 hPa for the analysed species) are available for download through:
        <ul>
          <li>the web using the ECMWF data server web interface: http://apps.ecmwf.int/datasets/data/macc-reanalysis/levtype=sfc/ , one month at a time
        <li>WebAPI, which is the method allowing users to download Global CAMS data in a programmatic way (using Python - example scripts are available).
  </ul>
<li>    NEW! 27 Mar 2018 The first 5 years of the CAMS reanalysis (2003-2007) now available! By the end of 2018, the CAMS Reanalysis data will cover the period January 2003 to near real time (NRT). For further details please see CAMS Reanalysis data documentation. Data download is through Web-API.
</ul>

<h3>Regional CAMS data (European domain, 25W/50E/30N/70N):</h3>
<ul>
  <li>All CAMS regional analysis and forecast daily data (archived since 10/2015 and less than 30 days old data, approximately 10km horizontal resolution from surface up to 5000m) are available for download either through:
        <ul><li>CAMS Regional data web interface for online (less than 30 days old) and Archive (older than 30 days) data access. 
        REST API for automated access by scripting (does not allow specific geographical area and/or level data extraction - unique token for all) - More details available here.
        <li>Push mode by subscription on data server (registration needed - please see Documentation)
        WMS and WCS API services (maps and data download - account needed)
          </ul>
    <li>CAMS regional reanalyses data are available online. 
  <li>Regional CAMS Data SAMPLES here
    </ul>
    
<h3>Supplementary Products: Solar and UV Radiation data:</h3>    
<ul>     
  <li>Solar radiation (2004 - present with up to 2 days delay) - global clear-sky solar irradiance and Meteosat satellite field-of-view coverage total-sky surface solar irradiation
        <ul>
          <li>interactive access through web-based graphical user interface (user registration needed)
        <li>automated way via WPS or WGET
        <br>Note: The CAMS Radiation Service currently is a time series service, i.e., for one location per request only. However a gridded solar radiation dataset for Europe is now available for download.
          </ul>
    <li>Global UV radiation archived data (see KB article)
        <ul>
          <li>Latest three days of near-real-time (NRT) CAMS global UV data are available through the FTP Dissemination server.
        <li>Archived data (since 01/06/2016, available with a 5-day delay) are available for download through:
            <ul>
              <li>the web using the ECMWF data server web interface: http://apps.ecmwf.int/datasets/data/cams-nrealtime/levtype=sfc/ , one month at a time
            <li>WebAPI, which is the method allowing users to download Global CAMS data in a programmatic way (using Python - example scripts are available).
            </ul>
          </ul>
      </ul>
<h3>Supplementary Products: Emission products, climate forcings and Greenhouse Gases (GHG) flux inversions data:</h3>
    <ul>
  <li>Anthropogenic emissions (2003-2009 European data on request and 1960-2020 global data through ECCAD)
    2003-2012 Climate forcings (e.g. aerosol direct/indirect forcing) through the ECMWF data server web interface: http://apps.ecmwf.int/datasets/data/cams-climate-forcings/
    <li>GFAS (Global Fire Assimilation System)
        <ul>
          <li>Latest seven days of GFAS data are available through the FTP Dissemination server.
        <li>GFAS archived data (2003 to yesterday) are available for download through:
            <ul><li>the web using the ECMWF data server web interface:http://apps.ecmwf.int/datasets/data/cams-gfas/
            <li>WebAPI, which is the method allowing users to download CAMS data in a programmatic way (using Python - example scripts are available).
              </ul>
          </ul>
    <li>Greenhouse Gases (GHG) flux inversions:
        <br>Carbon Dioxide (1979-2015), Methane (2000-2015) and Nitrous Oxide (1996-2015) through the ECMWF data server web interface: http://apps.ecmwf.int/datasets/data/cams-ghg-inversions/
             </ul>
<h3>    Forecast and Analysis Charts
    Forecast and Analysis Maps</h3>

    CAMS Monitoring Plots
    Near-real-time Analysis and Forecast of reactive gases (C-IFS)
    Forecast of UV Radiation
    Fire Radiative Power (archive)
    GHG forecasts
    Forecast of Aerosols Optical Depth
    MACC Reanalysis Monthly Mean fields
    MACC Reanalysis Monthly Mean Total Columns



<h3>ECMWF WCS (web covering service) - not needed?</h3>


