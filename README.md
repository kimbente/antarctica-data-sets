# Antarctic data sets
Overview of available data sets under the public domains which may be suitable for translational data science projects within Antarctic research. 

## Institutional data providers

* [NSIDC](https://nsidc.org/home) (The [US] National Snow and Ice Data Center) - contains a wide variety of cryosphere data sets including airborne, ground-based and satellite measurements. Many are continent wide.
  * [NSIDC data explorer](https://nsidc.org/data/explore-data). Select "Antarctica" as geographic area.
  * [Earthdata cryosphere website](https://www.earthdata.nasa.gov/topics/cryosphere)
  * [Earthdata - NASA's National Snow and Ice Data Center (NSIDC) Distributed Active Archive Center (DAAC)](https://www.earthdata.nasa.gov/eosdis/daacs/nsidc)
  * [Earthdata NSIDC DAAC webinars](https://www.earthdata.nasa.gov/learn/webinars-and-tutorials/nsidc-daac-24-aug-2022)
  * [NSIDC data tutorials](https://github.com/nsidc/NSIDC-Data-Tutorials)
* [Quantarctica data collection](https://www.npolar.no/en/quantarctica/) by the Norsk PolarInstitute has a collection of Antarctic geographical datasets.
* [BAS Discovery Metadata System](https://data.bas.ac.uk/terms.php?topic=Cryosphere) (Bristish Antarctic Survey). Cryosphere data sets. Select "Glaciers/Ice Sheets". Included Bedmap data sets.
* [SCAR](https://scar.org/resources/data/) (Scientific Committee on Antarctic Research) - included for example seismic data and iceberg data
  * [Antarctic Metadata Directory (AMD) on Earthdata](https://search.earthdata.nasa.gov/portal/amd/search)
  * [SCAR ADD  topographic data sets](https://www.bas.ac.uk/project/add/) (Scientific Committee on Antarctic Research, Antarctic Digital Database) - topographic data managed by the British Antarctic Survey (BAS)
* [NOAA NCEI](https://www.ncei.noaa.gov/products/paleoclimatology/ice-core) (The [US] National Oceanic and Atmospheric Administration, National Centers for Environmental Information)] - paleoclimatology datasets including ice core data
  * [NOAA NCEI data sets by location](https://www.ncei.noaa.gov/access/paleo-search/reports/location?dataTypeId=7&search=true)
* [NSF-ICF](https://icecores.org/inventory) (The [US] National Science Foundation Ice Core Facility) - stores and studies ice cores recovered from glaciated regions around the world. As of mid 2022, this includes ice cores from 18 areas in Antarctica.

## Other overviews of data and models

* [Pangaea](https://www.pangaea.de/?t=Cryosphere) (Data Publisher for Earth & Environmental Science) - Tool allows search for e.g. cryosphere data and more specifically for sampling/ice drillings.
* [Cryosphere links repository](https://github.com/tom-andersson/cryosphere-links)
* [AntarcticGlaciers website](https://www.antarcticglaciers.org/antarctica-2/antarctic-datasets/)

## Modelled/simulated data
* Bedmap2
  * key publication [Fretwell et al. 2013](https://tc.copernicus.org/articles/7/375/2013/)
  * [data](https://www.bas.ac.uk/project/bedmap-2/)
  * variables: surface elevation, ice thickness, bed elevation
* BedMachine
  * key publication (awaiting v3 Antarctica publication) [Morlighem et al. 2020](https://www.nature.com/articles/s41561-019-0510-8)
  * [data, MEaSUREs BedMachine Antarctica, Version 3](https://nsidc.org/data/nsidc-0756/versions/3) 
* RACMO
  * key publication [van Wessen et al. 2018](https://tc.copernicus.org/articles/12/1479/2018/)
  * [data](https://www.projects.science.uu.nl/iceclimate/publications/data/2018/vwessem2018_tc/RACMO_Yearly/)
* ECMWF Reanalysis v5 (ERA5)
  * key publication [Hersbach et al. 2020](https://rmets.onlinelibrary.wiley.com/doi/full/10.1002/qj.3803?ref=https://githubhelp.com)
  * [data](https://www.ecmwf.int/en/forecasts/dataset/ecmwf-reanalysis-v5)
  
## In-situ data
* Lora Koenig and Lynn Montgomery. 2019. [Surface Mass Balance and Snow Depth on Sea Ice Working Group (SUMup) accumulation on land ice subdataset](https://arcticdata.io/catalog/view/doi:10.18739/A2ZS2KD0Z), Greenland and Antarctica, 1987-2018. Arctic Data Center. doi:10.18739/A2ZS2KD0Z.

* ECMWF Reanalysis v5 (ERA5)

## Continent wide data by variable

* Ice velocity data
  * key publication 1 [Rignot et al. 2011](https://www.science.org/doi/full/10.1126/science.1208336?casa_token=g2LgmFsTJPkAAAAA%3AlVOZ7HeKsNPfROZvvzWzlGnnE5LTb5EQbojhwVWznZWTXbA9N31AAHGUNATPT0B9rHcqwhCumwtMdEhf#core-R22)
  * key publication 2 [Mouginot et al. 2012](https://www.mdpi.com/2072-4292/4/9/2753)
  * key publication 3 [Mouginot et al. 2017](https://www.mdpi.com/2072-4292/9/4/364)
  * [data: MEaSUREs InSAR-Based Antarctica Ice Velocity Map, Version 2](https://nsidc.org/data/nsidc-0484/versions/2)
    * 450m grid. Polar Stereographic projection
* SMB/Snow accumulation data
  * key publication [Arthern et el. 2006](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2004JD005667)
  * [data](https://legacy.bas.ac.uk/bas_research/data/online_resources/snow_accumulation/amsr_accumulation_map.txt)
  * Also see RACMO2 above
* Wind
* Geothermal heatflux/basal temperature
  * Key publication [Van Liefferinge and Pattyn 2013](https://cp.copernicus.org/articles/9/2335/2013/)
  * [Pattyn 2010](https://www.sciencedirect.com/science/article/pii/S0012821X10002712)
  * no data available
  * Other publication [An et al. 2015](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2015JB011917)
  * [data](http://www.seismolab.org/model/antarctica/lithosphere/index.html#an1-hf)

## Important research operations

* [NASA's Operation Icebridge](https://icebridge.gsfc.nasa.gov/)
  * Most data are not gridded; an exception is the Digital Elevation Model (DEM)
  * This mission bridges the temporal gap (~ 2009-2019) between NASA ICESat and ICESat-2
* [NASA Making Earth System Data Records for Use in Research Environments (MEaSUREs) Program](https://nsidc.org/data/measures)
  * Data sets adhere to high data standards.
  * [MEaSUREs InSAR-Based Antarctica Ice Velocity Map, Version 2 (NSIDC-0484)](https://nsidc.org/data/nsidc-0484/versions/2). Rignot et al. 2011.
  * [MEaSUREs Grounding Zone of the Antarctic Ice Sheet, Version 1 (NSIDC-0778)](https://nsidc.org/data/nsidc-0778/versions/1). Grounding line available as well.
  * [MEaSUREs MODIS Mosaic of Antarctica 2013-2014 (MOA2014) Image Map, Version 1 (NSIDC-0730)](https://nsidc.org/data/nsidc-0730/versions/1)  a snow grain size map and a surface morphology map. Snow grain size is related to the albedo.
  * [MEaSUREs Calibrated Enhanced-Resolution Passive Microwave Daily EASE-Grid 2.0 Brightness Temperature ESDR, Version 1 (NSIDC-0630)](https://nsidc.org/data/nsidc-0630/versions/1). Global data.
* GRACE
* ALBMAP
* Seismolab (Chinese Academy of Geological Sciences)
  * [lithosphere data](http://www.seismolab.org/model/antarctica/lithosphere/index.html)
  * [glacier velocity data](http://www.seismolab.org/model/antarctica/glacier/index.html)
  
## Data by locations

### Little Dome C

This area is of particular interest to paleoclimatology researchers. A current project is the [Million year ice core project](https://www.antarctica.gov.au/science/climate-processes-and-change/antarctic-palaeoclimate/million-year-ice-core/) led by the Australian Antarctic Division. Furthermore there is the [Beyond EPICA (European Project for Ice Coring in Antarctica) project](https://www.beyondepica.eu/en/) leb by European researchs.

* [Ice radar data from Little Dome C, Antarctica, 2016-2018](https://data.bas.ac.uk/metadata.php?id=GB/NERC/BAS/PDC/01623)

### Ross Ice Sheet

* [ROSETTA-Ice](https://pgg.ldeo.columbia.edu/data/rosetta-ice) is an airborne geophysical survey of the Ross Ice Shelf in Antarctica. The survey was conducted throughout three Antarctic seasons (2015 - 2016, 2016 - 2017, and 2017 - 2018). The instruments deployed include the IcePod, ZLS Gravimeter, DgS Gravimeter, and iMAR Gravimeter
* [SWAIS 2C](https://www.antarcticanz.govt.nz/media/news/drilling-into-antarcticas-past-to-see-our-future) project by Antarctica New Zealand. The Antarctic research project will investigate the sensitivity of the West Antarctic Ice Sheet to global warming of 2°C (SWAIS 2C) by retrieving sediment from the depths in a bid to find out how the ice behaved when global temperatures were as warm as those expected in the coming decades.

### Vostok (important ice core drilling site)
* Age of the Vostok ice core [link to Pangaea](https://doi.pangaea.de/10.1594/PANGAEA.55504)

### McMurdo Dry Valleys
* Antarctic Airborne ElectroMagnetics (ANTAEM) [link to Aarhus HydroGeophysics Group](https://hgg.au.dk/projects/antaem-antarctica-aem)

# License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
