TGRASS: temporal data processing with GRASS GIS
===============================================

This repo was created for the workshop **TGRASS: temporal data processing with GRASS GIS** at FOSS4G Europe 2017 in Paris (https://europe.foss4g.org/2017/Workshops).

Abstract
--------

GRASS GIS is a general purpose Free and Open Source geographic information system (GIS) that offers raster, 3D raster and vector data processing support. Since the initial release of the version 7, in February 2015, GRASS GIS has also oficially incorporated a powerful support for time series (TGRASS). Through this, GRASS GIS became the first open source temporal GIS with comprehensive spatio-temporal analysis, processing and visualization capabilities. The new functionality makes it easy to manage, analyse and visualize for example climatic data, vegetation index time series, harvest data or landuse changes over time.
Time series are handled through a new specific data type called space time data sets (stds) which are used as input in TGRASS modules. TGRASS incredibly simplifies the processing and analysis of large time series of hundreds of thousands of maps. For example, users can aggregate a daily time series into a monthly time series in just one line; get the date per year in which a certain value is reached; select maps from a time series in time periods in which a different time series reaches a certain value, perform different temporal as well as spatial operations among time series, and so much more.

In this 4-hours workshop we will present and exemplify the use of a subset of the more than 45 temporal modules in combination with other GRASS GIS modules and Add-ons in a workflow starting from the download of remote sensing data to the creation of a simple model and visualization of results. We will go through the creation of time series (stds) and registration of maps, reconstruction of incomplete data, temporal aggregation, queries and obtaining of statistics, as well as  time series visualization and animation. Moreover, we will show how this workflow might be included in python scripts and executed from outside GRASS GIS. 

First steps
-----------

*Software requirements:*
* GRASS GIS 7.4: 
  * Stand-alone installer: https://grass.osgeo.org/download/software/
  * OSGeo-live: https://live.osgeo.org/
 
* GRASS GIS Add-ons: 
  * i.modis: https://grass.osgeo.org/grass74/manuals/addons/i.modis
  * v.strds.stats: https://grass.osgeo.org/grass74/manuals/addons/v.strds.stats.html

* pyModis library: http://www.pymodis.org


*Sample data:*
* North Carolina basic location (50 MB): https://grass.osgeo.org/sampledata/north_carolina/nc_basic_spm_grass7.tar.gz

Register at NASA to be able to download MODIS data (https://urs.earthdata.nasa.gov/users/new). Once registered, log in and go to your profile page. In **My application** tab, approve the following applications *LP DAAC Data Pool* and *Earthdata Search*.

Enjoy! 

Authors
-------

* Veronica Andreo
* Luca Delucchi
* Markus Neteler

License
-------

The workshop text and images:

* Creative Commons Attribution-ShareAlike 4.0 International License

JavaScript code for tabs and other things:

* BSD 2-Clause License

Some other content is included too:

* jQuery library (MIT license)
* higlight.js (BSD 3-Clause License)
* GRASS GIS CSS file
* Python and CC logos

See specific files for thier licenses.
