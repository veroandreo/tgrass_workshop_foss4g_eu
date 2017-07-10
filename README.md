TGRASS: temporal data processing with GRASS GIS
===============================================

This repo was created for the workshop **TGRASS: temporal data processing with GRASS GIS** at FOSS4G Europe 2017 in Paris (https://europe.foss4g.org/2017/Workshops).

Abstract
--------

GRASS GIS is a Free and Open Source geographic information system (GIS) with support for raster, 3D raster and vector data processing. It provides more than 450 core modules, plus hundreds of Add-ons, to run any kind of geographical analysis. GRASS GIS offers a useful graphical interface to work as in any other desktop software. However, the highest power of GRASS GIS resides in that it can be used also like a backend tool to run analysis in an automatic way, not only a personal computer, but also into HPC systems or via web services (WPS or scripting in several languages). The workshop will show the basics about GRASS GIS, it will be an intuitive mix of theoretical and hands-on sections. In the former, we will introduce the participants to some specific concepts of GRASS GIS, like its database structure, location, mapset and region and will show how simple the approach really is. During the hands-on part, the participants will learn how to use common geographical data formats in GRASS GIS, starting from simple actions like adding data into the GRASS GIS environment and displaying it. Finally, the participants will run simple analyses like map algebra calculations for raster maps and vector buffering and visualize and export the results.

First steps
-----------

Software requirements:
* GRASS GIS 7.2: 
 * Stand-alone installer: https://grass.osgeo.org/download/software/
 * OSGeo-live: https://live.osgeo.org/
 
* GRASS GIS Add-ons: 
 * r.modis: https://grass.osgeo.org/grass72/manuals/addons/r.modis
 * v.strds.stats: https://grass.osgeo.org/grass72/manuals/addons/v.strds.stats.html
* pyModis library: http://www.pymodis.org

Sample data:
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
