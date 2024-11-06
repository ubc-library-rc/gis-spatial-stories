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
[QGIS](https://qgis.org/) is a popular desktop GIS software, and considered a **f**ree and **o**pen **s**ource **s**oftware **(FOSS)** with a very active development community. QGIS can be downloaded from [qgis.org/download/](https://qgis.org/download/). In most cases, you’ll want to download and install the Long Term Release (LTR) instead of the latest release. This will give you most of the functionality you’ll need, without encountering the software bugs of newly released versions.

The best way to learn QGIS is through experience and hands-on practice.QGIS comes with a low-to-medium learning curve, especially if you've never used a GIS before. However, there is a an abundance of QGIS-official and unofficial documentation on the internet in the form of tutorials and youtube demonstrations. This means you can tailer your learning experience to specifically what you want to do. 

> #### QGIS Advantages  ⇡
> {: .no_toc}
> - Free and open source 
> - Runs on Windows, Mac, Linux, Android
> - Extensive online documentation 
> - Intuitive interface
> - Active development and user communities, meaning people are constantly posing and answering questions on platforms such as Reddit and StackExchange. This makes troubleshooting a whole lot easier. 
> - Robust [plugin](https://plugins.qgis.org/) repository for extended functionality

> #### QGIS Disadvantages ⇣
> {: .no_toc}
> - Most recent features can be buggy, which is why we recommend always downloading the latest Long Term Release, often small hyperlink below main download button. 
> - Plugins lack standardized documentation as they are largely user-community developed and contributed
> - Troubleshooting often amounts to searching the web, though this is an important skill to have as a cartographer. 


#### QGIS Resources 
{: .no_toc}
- UBC Research Commons has two workshops to get you started: [Intro to Map Production with QGIS](https://ubc-library-rc.github.io/gis-intro-qgis/) and [Tools and Workflows in QGIS](https://ubc-library-rc.github.io/gis-tools-workflows/). 
- QGIS itself has extensive online documentation, including a robust [User Guide](https://docs.qgis.org/3.34/en/docs/user_manual/index.html#) *and* [Training Manual](https://docs.qgis.org/3.34/en/docs/training_manual/index.html). QGIS also has a vibrant user community, with answers to nearly any question you might have only a web search away. Many helpful tutorial demonstrations can be found on Youtube. [CWU Geography](https://www.youtube.com/@cwugeography3290) offers especially clear and helpful content. 
<!-- - [making a heatmap in QGIS](https://www.qgistutorials.com/en/docs/3/creating_heatmaps.html) -->
    
<br>
### ArcGIS Pro 
[ArcGIS Pro](https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview) is a proprietary desktop GIS that requires either a personal or institutional license. If you are faculty or student at UBC, you can learn more about obtaining access [here](https://gis.ubc.ca/software/#:~:text=FOR%20STUDENT%20PERSONAL%20COMPUTERS&text=This%20%2420%20license%20includes%20ArcGIS,reduced%20cost%20is%20also%20available.&text=This%20is%20a%20non%2Drefundable,installed%20on%20personal%20computers%20only.). ArcGIS has a medium learning curve. There is moderate documentation online, and while Esri offers training courses they often require payment to attend. 


> #### ArcGIS Advantages  ⇡
> {: .no_toc}
> - Advanced suite of tools for vector analysis and image processing, including both 2D and 3D visualization. 
> - Companies that have the means to purchase industry licenses will often expect employees to know ArcGIS. 

> #### ArcGIS Disadvantages ⇣
> {: .no_toc}
> - ArcGIS Pro is a proprietary software, meaning it is not free to download and you cannot view the program's source code.
> - ArcGIS Pro only runs on Windows operating system. If you have a license, you can log in on a Windows computer such as those in Koerner Library or use something like [Parallels](https://www.parallels.com/products/desktop/) to run a virtual Windows machine on your mac. However, this latter option takes up a lot of processing power on your computer, meaning it's likely to crash often and wear out your battery. 
> - Licensing is a hassle, and collaboration can only occur between people who both own an active license. 


### Other open-source GIS platforms
{: .no_toc}
While this workshop favors QGIS and the Research Commons exclusively runs QGIS workshops, [Open Jump GIS](https://www.openjump.org/) and [Grass GIS](https://grass.osgeo.org/) are two other open-source GIS platforms out there. 


----


## Non GIS options for making static maps
If you just want a quick reference map and don't want to use a GIS, you have a couple of options. You can also use illustration software either to make an entire rudimentary map using SVG vector graphics, or to embellish an initial map produced with a GIS. 

### MyOSMatic
[MapOSMatic](https://print.get-map.org/)"MapOSMatic is a free software webservice to generate maps of cities using OpenStreetMap data". Create rudimentary city map in just a few clicks! Difficulty low, but little room for customization.
no expertise necessary

### Static Map Maker
[Static Map Maker](https://staticmapmaker.com/mapbox/) allows you to easily create and download a static map from the web just by pasting some information into its parameters. You can choose from Bing, Google Maps, Google Street View, HERE, and MapQuest basemaps. Once you've selected a basemap provider of your choise, you will notice it says "authentication required". You _will_ need an API key (access token) to use any of the basemaps. (Scroll down to where it says _How to use_ and there will be a hyperlink to get an API key for the respective basemap.) While all these platforms are proprietary, you can create a free Mapbox account for an API key.  


### Map Creator
If you don't want to use a GIS yet want more aesthetic static maps than the above option can offer, [Mapcreator](https://mapcreator.io/) may be of interest. Web interface --> Paid subscription - tiers are all pricy. Can try a 14 day free trial. Notice that they are often using OpenStreetMap data, which is free and open source and can be freely used by you in either QGIS or MyOSMatic. 


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
- [Cartographic Design](https://colorado.pressbooks.pub/makingmaps/chapter/cartographic-design-process/)
- [Visual Hierarchy and Layout for maps](https://gistbok-topics.ucgis.org/CV-03-007)
    


- [Color Brewer](https://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3) helps you create an appealing color scheme based on the number of classes you have. 
- [Build a colorblind friendly palette](https://davidmathlogic.com/colorblind/#%23D81B60-%231E88E5-%23FFC107-%23004D40) based on a color of your choice. 

