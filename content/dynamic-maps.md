---
layout: default
title: Dynamic Maps
nav_order: 6
parent: Determining Output
---
# Dynamic Maps 
{: .no_toc}

Dynamic maps are interactive, allowing the user to reveal more information by zooming, clicking, and panning around. Dynamic, interactive narratives are not designed to be printed out. Rather, they are hosted on the web, either by a local server or internet hosting platform. This workshop will elaborate two kinds of dynamic maps you might find helpful to tell a spatial story: **Web maps** and **Narrative maps**.

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
 - TOC
{:toc}
</details>

----

## Web Maps 
Web maps are a means of visualizing and interacting with geographic data. Following the definition above, a web map is a type of digital map since it is derived from a computer. However, there are some important differences:
- **Dynamic scales and content** Web maps are not static images. Different scales display varying levels of detail. For instance, zooming in may reveal information that wasn't apparent before. For this reason, web maps are not designed for print.
- **Interactive** Web maps are built to be interacted with by an end user, often in order for the user to explore a dataset and learn something. Take for example Climate Central's [Surging Seas Risk Zone Map](https://ss2.climatecentral.org/#12/40.7298/-74.0070?show=satellite&projections=0-K14_RCP85-SLR&level=5&unit=feet&pois=hide). Or, listen to the radio anywhere in the world with [radio.garden](http://radio.garden/visit/vancouver/Lc5d7EdP)
- **Display real-time data updates** Web maps are useful for geovisualizing real-time data like weather. Watch [the wind blow across the country.](https://www.ventusky.com/?p=43.8;-97.3;5&l=temperature-2m)
- **Often rely on web and mobile technology** Web maps are ubiquitous - we see and use them all the time. For example, [Google Maps](https://www.google.ca/maps). For small businesses, web maps are helpful for [finding directions](https://luppolobrewing.ca/contact/). For app builders, web maps might provide a [method for routing to locations](https://www.pogomap.info/) using a mobile device's geolocation features. For researchers, they may help [communicate important information](https://www.uvic.ca/research/centres/cisur/projects/map/index.php) in an area of study. For journalists, they may give spatial context to a story like [where Amazon locates its warehouses and why](https://storymaps.arcgis.com/stories/adc5ff253a3643f88d39e7f3ef1a09ee).


The **Assembling Resources** section of this workshop will explain the various platforms in greater detail, including the advantages and disadvantages of each. For now, you'll be introduced to some examples so you can get a feel for what might work for you. You can create all the same reference and thematic maps introduced in the Static Map section with web maps. 

----


### Reference Webmaps
Much like their static counterparts, reference webmaps can be as simple as a basemap with a drop-pin locator or a single data layer. Explore the interactive capabilities of each. 

<iframe src="./reference/leaflet-reference-map.html" style="width:90%; height:450px; border:none;"> </iframe>

<iframe src="https://www.google.com/maps/d/embed?mid=1aslINORADirq1Cx5_mRG4s2EO2OfxF4&hl=en&ehbc=2E312F" width="640" height="480"></iframe>


Some popular reference webmaps out there:
<iframe src="https://native-land.ca/" width="640" height="640"></iframe>

<iframe src="https://www.queeringthemap.com/" width="640" height="640"></iframe>



*Maybe add an example that's like: a nice walk I took.*


### Thematic Webmaps 
Thematic maps visualize the results of some spatial analysis. With a bit of code, you can create thematic webmaps. 

<!-- While you can do this spatial analysis in QGIS and then export your data or map... You can also use Leaflet or Mapbox to power the spatial analysis for you through functions. Like cluster, heatmap, etc.  -->

<sub>[See below choropleth example as full-page map](./reference/leaflet-choropleth-map.html)</sub>
<iframe src="./reference/leaflet-choropleth-map.html" style="width:90%; height:400px; border:none;"> </iframe>

  
<sub>[See below cluster map example as full-page map](./reference/leaflet-cluster-map.html)</sub>
<iframe src="./reference/leaflet-cluster-map.html" style="width:90%; height:450px; border:none;"> </iframe>
    
<sub>[See below cluster map example as full-page map](./reference/mapbox-cluster-map.html)</sub>
<iframe src="./reference/mapbox-cluster-map.html" style="width:90%; height:400px; border:none; "></iframe>


<sub>[See below proportional symbol map example as full-page map](./reference/leaflet-proportional-symbol-map.html)</sub> Hover over the circles to learn the municipality population for Vancouver Island.
<iframe src="./reference/leaflet-proportional-symbol-map.html" style="width:90%; height:450px; border:none; "></iframe>


---
## Narrative Maps  
Narrative maps tell a story with images and text at locations, by a thread - perhaps linear. changing frame brings the visitor on a journey. For example, a timeline, a travel voyage. Below are some examples by different hosting platforms. Assembling Resources section will go further into advantages and disadvantages of each. 


- [Canada's Deforestation monitoring storymap](https://ca.nfis.org/ndms/ndms_overview_eng.html)

- [Ancient Rome in Chicago](https://s3.amazonaws.com/uploads.knightlab.com/storymapjs/783a09de8300e1b5f74b99b99acb08ef/ancient-rome-in-chicago/index.html) 

- [Urban Tree tour](https://kamloops.maps.arcgis.com/apps/Shortlist/index.html?appid=96ba7bf46e4f45f484e872fd47c9a004) 

- [Isolation Psychogeography](https://storymaps.arcgis.com/stories/4ab243f6d7b3490bbfa884d18a788236)


- [archeology of wine](https://timemapper.okfnlabs.org/adamrabinowitz/archaeowinetimeliner)



- [Google Earth]
Add a google story maps walking path example. 
or leaflet --> maybe qgis incorperated. 

https://www.google.com/maps/about/behind-the-scenes/streetview/treks/yosemite/#trek



https://www.google.com/earth/outreach/learn/create-a-map-or-story-in-google-earth-web/


<!-- ### Interactive Dashboards 
Interactive dashboards, combine maps - more info. ...
 showing things  customizing (open source and non open source options)

- give examples that use leaflet, mapbox, agol, google, felt,

**Examples**
- [Leaflet dashboard]
- [ArcGIS Online dashboard](https://www.esri.com/en-us/arcgis/products/arcgis-dashboards/overview)
- [Felt](https://felt.com/)
- [Google Maps Platform](https://mapsplatform.google.com/) 
using r shiny https://rstudio.github.io/leaflet/articles/shiny.html -->
