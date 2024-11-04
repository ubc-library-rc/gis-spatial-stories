---
layout: default
title: Static Maps & Spatial Analysis
nav_order: 2
parent: Assembling Resources
---
# Resources for Static Mapping & Spatial Analysis
{: .no_toc}

This page will inventory a variety of platforms, tools, and resources for making static maps, whether they be reference maps or thematic maps. Generally, if you are making a thematic map you will need to use a geographic information system (GIS) of some sort. 

<!-- At a glance, 
- what it is; useful for xyz
- advantages and disadvantages 
- difficulty/learning curve
- access/ open source or proprietary 
for all, give 
- examples (more than in determine output section?)

Resources
- links to download tool
- links to task specific plugins
- links to tutorials and demos  -->

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
 - TOC
{:toc}
</details>

----

## Geographic Information Systems

### QGIS
[QGIS](https://qgis.org/) is a popular desktop GIS software, and considered a **f**ree and **o**pen **s**ource **s**oftware **(FOSS)** with a very active development community. QGIS can be downloaded from qgis.org’s [Downloads](https://qgis.org/download/) page. In most cases, you’ll want to download and install the Long term release instead of the latest release. This will give you most of the functionality you’ll need, without encountering the software bugs of newly released versions.

QGIS comes with a medium learning curve, especially if you've never used a GIS before. However, there is a an abundance of QGIS-official and unofficial documentation on the internet in the form of tutorials and youtube demonstrations, meaning you can tailer your learning experience to specifically what you want to do. The best way to learn QGIS is through experience and hands-on practice.

> #### QGIS Advantages  ⇡
> {: .no_toc}
> - Runs on Windows, Mac, Linux, Android
> - Extensive QGIS-official [online documentation](https://docs.qgis.org/3.28/en/docs/training_manual/index.html)
> - Active development and user communities, meaning people are constantly posing and answering questions on conversational/troubleshooting platforms such as Reddit and StackExchange 
> - Robust [plugin](https://plugins.qgis.org/) repository for extended functionality

> #### QGIS Disadvantages ⇣
> {: .no_toc}
> - Most recent features can be buggy, which is why we recommend always downloading the latest Long Term Release, often small hyperlink below main download button. 
> - Plugins lack standardized documentation as they are largely user-community developed and contributed
> - Troubleshooting often amounts to searching the web, though this is an important skill to have as a cartographer. 


#### QGIS Resources 
{: .no_toc}
- UBC Research Commons has two workshops to get you started: [Intro to Map Production with QGIS](https://ubc-library-rc.github.io/gis-intro-qgis/) and [Tools and Workflows in QGIS](https://ubc-library-rc.github.io/gis-tools-workflows/)
- QGIS itself has extensive online documentation, including a robust [User Guide](https://docs.qgis.org/3.34/en/docs/user_manual/index.html#) *and* [Training Manual](https://docs.qgis.org/3.34/en/docs/training_manual/index.html). QGIS also has a vibrant user community, with answers to nearly any question you might have only a web search away. Many helpful tutorial demonstrations can be found on Youtube. [CWU Geography](https://www.youtube.com/@cwugeography3290) has especially clear and helpful content. 
<!-- - [making a heatmap in QGIS](https://www.qgistutorials.com/en/docs/3/creating_heatmaps.html) -->

### ArcGIS Pro 
[ArcGIS Pro](https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview) is a proprietary desktop GIS that requires either a personal or institutional license. If you are faculty or student at UBC, you can learn more about obtaining access [here](https://gis.ubc.ca/software/#:~:text=FOR%20STUDENT%20PERSONAL%20COMPUTERS&text=This%20%2420%20license%20includes%20ArcGIS,reduced%20cost%20is%20also%20available.&text=This%20is%20a%20non%2Drefundable,installed%20on%20personal%20computers%20only.). ArcGIS has a medium learning curve. There is moderate documentation online, and while Esri offers training courses they often require payment to attend. 


> #### ArcGIS Advantages  ⇡
> {: .no_toc}
> - Suite of tools for vector analysis and image processing
> - ?

> #### ArcGIS Disadvantages ⇣
> {: .no_toc}
> - ArcGIS Pro only runs on Windows operating system 
> - ArcGIS Pro is a proprietary software
> - Licensing is a hassle, and collaboration can only occur between people with a license. 


### Other open-source GIS platforms
{: .no_toc}

While this workshop favors QGIS and the Research Commons exclusively runs QGIS workshops, [Open Jump GIS](https://www.openjump.org/) and [Grass GIS](https://grass.osgeo.org/) are two other open-source GIS platforms out there. 


----


## Non GIS options for making static maps
If you just want a quick reference map and don't want to use a GIS, couple of options. Also some illustration softwares detailed below that can be used on their own or in integrated workflow with GIS for more advanced cartography. 

### MyOSMatic
[MapOSMatic](https://print.get-map.org/)"MapOSMatic is a free software webservice to generate maps of cities using OpenStreetMap data". Create rudimentary city map in just a few clicks! Difficulty low, but little room for customization.
no expertise necessary

### Mapbox Studio
https://docs.mapbox.com/help/dive-deeper/static-maps/



<!-- ### Google Maps Platform
https://developers.google.com/maps -->

### Adobe Illustrator, GIMP, & Inkscape
These are there illustration software. 
Can download SVG vector data and work with in either. **[Adobe Illustrator](https://www.adobe.com/ca/products/illustrator.html)** is proprietary and costly. **[Inkscape](https://inkscape.org/release/inkscape-1.2.2/)** is a free and open-source alternative SVG editor. Steep learning curve if you are not familiar with interface such as Adobe Illustrator, but plenty of documentation online and handy tool to know. **[GIMP](https://www.gimp.org/)** - Free & Open Source Image Editor, akin to Adobe Photoshop. Can work with rasters here. 

----
## Resources for map design
- [Axis Maps Cartography Guide](https://www.axismaps.com/guide) offers tips for map design
- [DIY Cartography - Resources & Ideas](https://makingmaps.net/)
- [Books for the love of cartography by Gretchen N. Peterson](https://www.gretchenpeterson.com/) such as *[QGIS Map Design](https://locatepress.com/book/qmd2)* and *Cartographer's Toolkit*
- [Decolonizing the map](https://press.uchicago.edu/ucp/books/book/chicago/D/bo25338607.html)
- See more Cartographic Media from [CartoSquad](https://cartosquad.com/media.html)