TERRA SULIS RESEARCH CIC 
www.terrasulis.org

VERSION: 1.3
========

TITLE: Liberia Rivers, 1:200,000
=====

TYPE: ESRI Shape File
=====

COVERAGE: Liberia
========

DATA SOURCES:
=============
Shuttle Radar Terrain Model http://srtm.csi.cgiar.org
Landsat https://landsat.usgs.gov

MAP PROJECTION:
===============
Universal Transverse Mercator, Zone 29 North, EPSG:32629

DESCRIPTION:
============
The map is derived from Shuttle Radar Topographic Mission (SRTM) digital terrain data. Rivers have been extracted through a three stage process:

1. The SRTM terrain data were processed to derive runoff, assuming even rainfall across the whole country. The runoff map was then constrained to roughly match the perennial rivers in the Liberia Institute of Statistics and Geo-Information Services (LISGIS) map, which is a legacy map derived from aerial photography.
2. The location of the rivers in step 1 were then edited to spatially match the location of rivers on Landsat satellite imagery. Visible rivers were edited and given a ‘confidence’ attribute of 1. Non visible rivers were not edited and were given a ‘confidence’ attribute of 2. In some locations high resolution imagery was used to make corrections. 
3. The rivers were then generalised to be commensurate with a scale of 1:200,000 and smoothed to remove jagged edges. 

SCALE:
======
1 : 200,000

ATTRIBUTES:
===========
id		feature identifier
code		not used
version		version number
update		date updated
name		river name, used for annotation only
confidence	1 = corrected to Landsat, 2 = position calculated from SRTM
channel		1 = main channel


TERMS OF USE
=============

Liberia River Map 1:25,000 by Terra Sulis Research is a licensed data product. 

This map is suitable for display at the scale of 1:25,000 and comes with absolutely no warranty. 
