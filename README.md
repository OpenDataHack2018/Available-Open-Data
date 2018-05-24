# Available-Open-Data - Still under development!

<h3><a href="#C3S">From the ECMWF Copernicus Climate Change Service (C3S)</a></H3>
<h3><a href="#CAMS">From the ECMWF Copernicus Atmosphere Monitoring Service (CAMS)</a></H3>
<hr>


<h3>C3S ERA5 - Global Climate Reanalysis data (2008-present available now)</h3>
<ul>
<li><a href="https://software.ecmwf.int/wiki/display/CKB/What+is+ERA5">What is ERA5</a>
<li><a href="https://software.ecmwf.int/wiki/display/CKB/ERA5+data+documentation">ERA5 documentation</a>
<li>Download ERA5 data via the Climate Data Store - Soon to come!
<li>ERA5 data Samples available <a href="ftp://ftp.ecmwf.int/pub/copsup/OpenDataHack2018/">here</a>
</ul>

<!--
<h3>Seasonal Forecasts</H3>
<ul>
<li><a href="http://climate.copernicus.eu/s/charts/c3s_seasonal/">Charts</a> including: MSLP charts, SST maps and NINO-index timeseries, 2m Temperature charts, 850mb Temperature charts, Geopotential height at 500Pa  charts, Precipitation charts. The forecasts are updated every month and cover a time range of 6 months.
<li>Archived data in the Climate Data Store
<li>Seasonal forecast data Samples available <a href="ftp://ftp.ecmwf.int/pub/copsup/">here</a>
</ul>        
-->

<h3>C3S Data from the Sectoral Information System (SIS) for the WATER sector, ENERGY sector and INSURANCE sector</h3>
<ul>
<li><a href="http://edge.climate.copernicus.eu">End-to-end Demonstrator for improved decision making in the water sector in Europe (EDgE)</a>: EDgE is producing a climate information system <a href"http://edge.climate.copernicus.eu/Tools/">"Map Viewer"</a> to allow end-users to find, understand and access the range of climatological and hydrological data and indicators. 

<li><a href="http://swicca.eu/">Service for Water Indicators in Climate Change Adaption (SWICCA)</a> offers readily available <a href="http://swicca.eu/climate-impacts-maps/">climate-impact data, graphs and maps</a> to speed up the workflow in climate-change adaptation of water management across Europe.  

<li><a href="http://ecem.climate.copernicus.eu/">European Climatic Energy Mixes (ECEM)</a> is developing a <a href="http://ecem.climate.copernicus.eu/demonstrator/">Demonstrator</a> to enable the energy industry and policy makers to assess how well energy supply will meet demand in Europe over different time horizons, focusing on the role climate has on energy supply and demand.

<li><a href="http://clim4energy.climate.copernicus.eu/">CLIM4ENERGY</a> provides climate change indicators tailored for the energy sector. The <a href="http://c4e-visu.ipsl.upmc.fr/">Clim4energy visualization portal</a> is online, in beta-test. 

<li><a href="">Wind Storm Information Service (WISC)</a> provides historic storm data over Europe from 1940 onwards through the <a href="https://wisc.climate.copernicus.eu/wisc/#/explore">WISC Portal</a>.
</ul>

<h3>C3S Monthly State of Climate (Maps):</h3>
<ul>
  <li>Average surface air temperature monthly maps:
        <ul>
          <li><a href="https://climate.copernicus.eu/resources/data-analysis/average-surface-air-temperature-analysis">Latest monthly map</a>
    <li><a href="https://climate.copernicus.eu/resources/data-analysis/average-surface-air-temperature-analysis/monthly-maps/">Archived maps from August 2015.</a>
      </ul>
    <li>Monthly sea-ice maps:
        <ul><li><a href="https://climate.copernicus.eu/products/monthly-sea-ice-maps">Latest Monthly Maps</a>
        <li><a href="https://climate.copernicus.eu/sea-ice-monthly-maps">Archived maps from March 2017.</a>
      </ul>
    <li>Monthly summaries of precipitation, relative humidity and soil moisture:
        <ul><li><a href="https://climate.copernicus.eu/monthly-summaries-precipitation-relative-humidity-and-soil-moisture">Latest Monthly Maps</a>
        <li><a href="https://climate.copernicus.eu/precipitation-relative-humidity-and-soil-moisture-monthly-maps">Archived maps from April 2017</a>
          </ul>
 </ul>       

<h3>C3S Essential Climate Variables (ECVs) - Soon available through the CDS</h3>
<UL>
    <li>Sea ice concentration, sea ice edge and type, sea ice thickness
    <li>Sea level
    <li>Sea surface temperature (SST)
    <li>Ozone
    <li>Total column and vertical aerosol information
    <li>Carbon dioxide and methane
    <li>Soil moisture
    <li>Glaciers and ice caps
    <li>Surface albedo, leaf area index (LAI) and the fraction of absorbed photosynthetic active radiation (FAPAR)
</ul>

<a name="CAMS"></a>

<h3>CAMS Global data:</h3>

<ul>    
    <li>CAMS <strong>Global archived analysis and forecast daily data </strong> (6 hourly analysis and 3 hourly up-to 5 days forecast data since 05/07/2012, available with a 5-day delay, approximately 40km horizontal resolution (T511 spectral) on 60 vertical levels from the surface up to 0.1 hPa, are available for download through:
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

<h3>CAMS Regional data (European domain, 25W/50E/30N/70N):</h3>
<ul>
  <li>All CAMS regional analysis and forecast daily data (archived since 10/2015 and less than 30 days old data, approximately 10km horizontal resolution from surface up to 5000m) are available for download either through:
        <ul><li>CAMS Regional data web interface for online (less than 30 days old) and Archive (older than 30 days) data access. 
        REST API for automated access by scripting (does not allow specific geographical area and/or level data extraction - unique token for all) - More details available here.
        <li>Push mode by subscription on data server (registration needed - please see Documentation)
        WMS and WCS API services (maps and data download - account needed)
          </ul>
    <li>CAMS regional reanalyses data are available online. 
  <li>CAMS regional ensemble data sample at 3000 European locations available <a href="https://github.com/OpenDataHack2018/Available-Open-Data/blob/master/CAMS-regional-air-quality.md">here</a>.
    </ul>
    
<h3>CAMS Supplementary Products: Solar and UV Radiation data:</h3>    
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
<h3>CAMS Supplementary Products: Emission products, climate forcings and Greenhouse Gases (GHG) flux inversions data:</h3>
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
<h3>CAMS Forecast and Analysis Maps</h3>

    CAMS Monitoring Plots
    Near-real-time Analysis and Forecast of reactive gases (C-IFS)
    Forecast of UV Radiation
    Fire Radiative Power (archive)
    GHG forecasts
    Forecast of Aerosols Optical Depth
    MACC Reanalysis Monthly Mean fields
    MACC Reanalysis Monthly Mean Total Columns



<h3>ECMWF WCS (web covering service) - not needed?</h3>


