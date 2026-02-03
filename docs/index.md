---
title: "ArcGIS Pro Workshop Outline"
layout: "home"
description: "This tutorial will use 7 modules to teach you the basics of ArcGIS Pro. These modules will cover topics such as adding, manipulating, analyzing, and mapping vector and raster data."
staff:
    - name: Marcel Fortin
      link: https://library.utoronto.ca/staff/marcel-fortin
created_date: 2021-01-07
permalink: "/"  #! Remove this if not the homepage
---

# ArcGIS Pro Workshop Outline

This tutorial will use 7 modules to teach you the basics of ArcGIS Pro. These modules will cover topics such as adding, manipulating, analyzing, and mapping vector and raster data.

ArcGIS Pro Workshop outline and requirements
--------------------------------------------

Pre-Workshop Preparation
-------------------------

### ArcGIS Pro Installation

1. Request an esri license for ArcGIS Pro [https://mdl.library.utoronto.ca/technology/gis-software/esri-software-request](https://mdl.library.utoronto.ca/technology/gis-software/esri-software-request)
	* Instructions will be sent to you for download and installation when requesting the license
2. Setup an ArcGIS Online account [https://mdl.library.utoronto.ca/technology/tutorials/logging-arcgis-online](https://mdl.library.utoronto.ca/technology/tutorials/logging-arcgis-online)
3. Please note that ArcGIS and all Esri products run on the Windows operating system only. If you have a Mac and wish to run ArcGIS Pro on you computer, you will need to obtain a copy of Windows and run this operating system on a virtual machine on your computer. Emulating software to run Windows on your Mac include
	* [Virtual Box](https://www-oracle-com.myaccess.library.utoronto.ca/virtualization/virtualbox/) [free]
	* [BootCamp](https://support.apple.com/en-ca/boot-camp) [free and pre-loaded on macs] [dual boot - which means you can’t run both mac and windows operating systems at once]
	* [Parallels](https://www.parallels.com/) [~$80.00, but worth the money. It allows for running windows and mac operating systems at the same time and exchange files and even run windows programs in Mac look (not by default).

#### A note on QGIS

[QGIS](http://qgis.com/) is a powerful, free and open source full-featured GIS software package. It runs on Windows, Mac and Linux.

---

*Session 1*
===========

 

1. ### Introduction

    * [An Introduction to the MDL](https://maps.library.utoronto.ca/workshops/ArcGISProWorkshop/2021/00%20-%20MDL%20(2021).pdf)
    * [What is GIS?](https://maps-library-utoronto-ca.myaccess.library.utoronto.ca/workshops/ArcGISProWorkshop/2020/01%20-%20What%20is%20GIS_%20(2020).pdf)
    * [GIS data](https://maps-library-utoronto-ca.myaccess.library.utoronto.ca/workshops/ArcGISProWorkshop/2020/02%20-%20GIS%20Data%20(2020).pdf)
      * Vector vs. Raster
      * Attribute Data
    * [GIS Software](https://maps-library-utoronto-ca.myaccess.library.utoronto.ca/workshops/ArcGISProWorkshop/2020/03%20-%20GIS%20Software%20(2020).pdf)
2. ### Hands On Introduction to ArcGIS Pro

    * [An Overview](https://maps-library-utoronto-ca.myaccess.library.utoronto.ca/workshops/ArcGISProWorkshop/2020/04%20-%20ArcGIS%20Pro%20Modules%20Overview%20(2020).pdf)
    * [Download Data for this Workshop](https://maps-library-utoronto-ca.myaccess.library.utoronto.ca/workshops/ArcGISProWorkshop/2020/ArcGISProWorkshop2020.zip)
    * [Module 1 - Getting Started with ArcGIS Pro](https://maps-library-utoronto-ca.myaccess.library.utoronto.ca/workshops/ArcGISProWorkshop/2020/05%20-%20ArcGIS%20pro%20Module%201%20-%20A%20Tour%20of%20ArcGIS%20Pro%20(2020).pdf)
      + The basics
      + Loading and Manipulating data
      + Exporting a Basic Map
    * [Module 2 - Making a Printable Map](https://maps-library-utoronto-ca.myaccess.library.utoronto.ca/workshops/ArcGISProWorkshop/2020/06%20-%20ArcGIS%20Pro%20Module%202%20-%20Making%20a%20Map%20(2020).pdf)
      * legends
      * inset map
      * scale bar
      * title
      * north arrow
      * textual information

---

*Session 2*
===========

 

1. ### Continued Basics from Previous Session

    * [Module 3 Manipulating Data](https://maps-library-utoronto-ca.myaccess.library.utoronto.ca/workshops/ArcGISProWorkshop/2020/07%20-%20ArcGIS%20Pro%20Module%203%20-%20Loading%20and%20Manipulating%20Data%20(2020).pdf)
      + Adding data (vector, raster and attribute)
      + Map Projections
      + Querying and Symbolizing Attribute Data
      + Subsetting Data
      + Labelling Data
      + Formating Layer Files
      + Grouping Data
      + Mapping Services
      + Geocoding
2. ### Basic Geospatial Analytics

    * [Module 4 - An Introduction to Spatial Analysis](https://maps-library-utoronto-ca.myaccess.library.utoronto.ca/workshops/ArcGISProWorkshop/2020/08%20-%20ArcGIS%20Pro%20Module%204%20-%20Analysis%20Tools%20(2020).pdf)
      + Calculating Distances
      + Joins (Spatial and Attribute)
      + Summarizing Statistics
      + Charts
      + Advanced Mapping
      + Choropleth Mapping
      + Graduated Symbols
      + Proportional Symbols
      + Dot Density
      + Buffering
      + Erasing
      + Clipping
      + Selection
          - by Location
          - by Attributes
      + Site Selection
3. ### Raster GIS Analytics

    * [Module 5 - Raster Spatial Analysis](https://maps-library-utoronto-ca.myaccess.library.utoronto.ca/workshops/ArcGISProWorkshop/2020/09%20-%20ArcGIS%20Pro%20Module%205%20-%20Working%20with%20Raster%20Data%20(2020).pdf)
      + [Download Satellite Imagery Data](https://maps-library-utoronto-ca.myaccess.library.utoronto.ca/workshops/ArcGISProWorkshop/2020/landsat8.tar)
      + DEM And Land Classification Data Basics
      + Classifying Elevations
      + Generating Contour Lines
	  + Recalculating Values
      + Normalized Difference Vegetation Index
      + Extracting Values
      + Density Analysis (Spatial Analyst ArcGIS Pro Extension)
      + Historical Cholera Data of London (John Snow data)
      + Toronto Homicide data

    ---

*Session 3*
===========

### Finding and Mapping Data

 

1. ### Finding Data

    * [Module 6 - Locating Relevant Data](https://maps-library-utoronto-ca.myaccess.library.utoronto.ca/workshops/FindingGeoData/FindingGeohealthData2020.pdf)
      + US
	  + Canada
        + Ontario
	    + Toronto
2. ### Mapping Health Data

    * [Module 7 - Mapping Health Data](https://maps-library-utoronto-ca.myaccess.library.utoronto.ca/workshops/ArcGISProWorkshop/2020/10%20-%20ArcGIS%20Pro%20Module%207%20%20-%20Mapping%20Toronto%20Health%20Data%20(covid-19).pdf)
      + Mapping Toronto Health Data
      + Mapping Covid-19 Data
        - World
        - North America
          * US
          * Canada
            + Toronto

Technique: [Mapping](https://mdl.library.utoronto.ca/technique/mapping), [Spatial Analysis](https://mdl.library.utoronto.ca/technique/spatial-analysis) | Tools: [ArcGIS Pro](https://mdl.library.utoronto.ca/taxonomy/term/70)
