---
layout: default
title: Web Mapping
nav_order: 3
parent: Assembling Resources
---
# Resources for web mapping 
{: .no_toc}
This page will inventory a variety of platforms, tools, and resources for web mapping. 

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
 - TOC
{:toc}
</details>

----

## Leaflet
[Leaflet](https://leafletjs.com/) consists of JavaScript and CSS code libraries which power the ways your web browser interprets and interacts with geospatial data & displays colors and style. For instance, when you double click a map to zoom in, Leaflet is at work. When you add data to your map, Leaflet assigns it a default color. Leaflet is made up of only 38kb of Javascript, so it is really fast and lightweight - meaning browsers don’t have to work very hard to load it. 


> #### Leaflet Advantages  ⇡
> {: .no_toc}
> - Leaflet is free and open source. For this reason, Leaflet is widely used. 
- As an open-source code library, Leaflet is hugely customizable. This means you can re-mix the code all you want. 
> - Leaflet is beginner friendly. 
> - Hugely customizable code with ... [Here are some examples](https://leafletjs.com/plugins.html) of Leaflet-based plugins to give you some idea of the variety of added functionality that comes from the community of developers. 
> - In Leaflet, you can [change the CRS](https://leafletjs.com/reference.html#crs) of your map whereas the projection is set in Google Maps and Mapbox. 

> #### Leaflet Disadvantages ⇣
> {: .no_toc}
> - need to work in code editor --> link to it! 
> - 

#### Resources for working with Leaflet
{: .no_toc}
- UBC Research Commons' [Introduction to Leaflet](https://ubc-library-rc.github.io/gis-intro-leaflet/)
- [Leaflet Tutorials](https://leafletjs.com/examples.html) for getting started


#### Plugins/tutorials for basic thematic mapping
{: .no_toc}
Plugins offer extended functionality, making leaflet hugely customizable.
Here are some [example plugins](https://leafletjs.com/plugins.html) to give you some idea of the variety of added functionality that comes from the community of developers. 
- [Heatmaps with Leaflet](https://leafletjs.com/plugins.html#heatmaps)
- [Clustering](https://github.com/Leaflet/Leaflet.markercluster)
> - [see example](https://leaflet.github.io/Leaflet.markercluster/example/marker-clustering-realworld.388.html)


#### code for making dashboard / etc. 
{: .no_toc}
- [adding side panels/menus to leaflet map](https://unbam.github.io/Leaflet.SlideMenu/)
- [another side bar example](https://github.com/noerw/leaflet-sidebar-v2)
    > - [see demo here](https://noerw.github.io/leaflet-sidebar-v2/examples/)
- [leaflet marker cluster](https://github.com/leaflet/Leaflet.markercluster)
- [overlay layers control](https://leafletjs.com/examples/layers-control/)
- Create a [side panel](https://github.com/maxwell-ilai/Leaflet.SidePanel) (scroll down to see [example](https://maxwell-ilai.github.io/Leaflet.SidePanel/examples/))

----

## Mapbox
[Mapbox](https://www.mapbox.com/) is a robust Geospatial Software As A Service (saas) for developers, and includes products such as toolkits for mobile app development, navigation, web maps, and data management. Mapbox's service model is based on a paid subscription, but they offer a free service tier for those interested in using Mapbox products for learning. You will be asked to put in credit card information, however.  If this is your first time hearing about Mapbox, [How Mapbox Works](https://docs.mapbox.com/help/getting-started/) provides a great introduction.


> #### Mapbox Advantages  ⇡
> {: .no_toc}
> - Custom style basemaps
> - Can make webmaps with or without use of code --> Mapbox studio

> #### Mapbox Disadvantages ⇣
> {: .no_toc}
> - Proprietary. While there
> - Free tier --> limitations
> - Requires more knowledge to work in code --> less customizable

#### Resources for working with Mapbox
{: .no_toc}
- UBC Research Commons' [Intro to Mapbox](https://ubc-library-rc.github.io/intro-mapbox/) workshop
- [Intro to Mapbox studio](https://docs.mapbox.com/studio-manual/guides/)
- [Choropleth maps with Mapbox](https://labs.mapbox.com/education/thematic-map-types/choropleth/)
- [Heatmaps with Mapbox Studio](https://docs.mapbox.com/help/tutorials/studio-heatmap-tutorial/)
- [Dot Density maps with Mapbox](https://labs.mapbox.com/education/thematic-map-types/dot-density/)
- [Graduated Symbol maps with Mapbox](https://labs.mapbox.com/education/thematic-map-types/graduated-points/)

<!-- ----
## Zee Maps
[ZeeMaps](https://www.zeemaps.com/)
is 
tiered subscription service with free option. 
quick and easy option to convert spreadsheet data to thematic web map. 
 eg [make a choropleth map](https://www.zeemaps.com/world-of-maps/choropleth-map/) -->


----
## QGIS to Web

If you're familiar with QGIS, there's actually a plugin for turning your QGIS map into an interactive webmap, either powered by Leaflet or OpenLayers. This plugin is aptly called [qgis2web](https://plugins.qgis.org/plugins/qgis2web/). You just install the plugin, and then ensure your Field visibilities are set under layer --> propterties. However, you will need somewhere to store your map and map data. Github can work. 
[interactive filters](https://digital-geography.com/qgis2web-with-interactive-filters/)

Example from Map Created by Workshop Author for BC Disaster Resilience Research Network:
  <iframe src="./reference/qgis2web/index.html" style="width:100%; height:600px;"></iframe>


----
## ArcGIS Online
[ArcGIS Online](https://www.arcgis.com/index.html) or (AGOL)
is
does
As an Esri ArcGIS product, similar ArcGIS

#### ArcGIS Online Advantages  ⇡
{: .no_toc}

#### ArcGIS Online Disadvantages ⇣
{: .no_toc}

----

## Google Maps 

> #### Google Maps Advantages  ⇡
> {: .no_toc}
> - easy, straightforward, free

> #### Google Maps Disadvantages ⇣
> {: .no_toc}
> - 

----
## Felt
[Felt](https://felt.com/) is... what its good for 
has a free tier
[see gallary](https://felt.com/gallery) for [examples](https://felt.com/map/Baltimore-City-Proposed-Land-Use-April-2024-DEElrNXBRICZ3XTKtmCYKD?loc=39.34342,-76.63756,13.9z). 

----
## map libre
https://maplibre.org/
https://github.com/maplibre/maplibre-gl-js
https://maplibre.org/maplibre-gl-js/docs/

> "MapLibre GL JS is an open-source library for publishing maps on your websites or webview based apps. Fast displaying of maps is possible thanks to GPU-accelerated vector tile rendering.

  > It originated as an open-source fork of mapbox-gl-js, before their switch to a non-OSS license in December 2020. The library's initial versions (1.x) were intended to be a drop-in replacement for the Mapbox’s OSS version (1.x) with additional functionality, but have evolved a lot since then."


---- 

## uMap
[uMap](https://umap.openstreetmap.fr/en/): "uMap lets you create maps with OpenStreetMap layers in a minute and embed them in your site." is open source, free to use. can add data layers.


    
https://www.maptiler.com/data/

https://openmaptiles.org/docs/style/maputnik/

https://stadiamaps.com/
put also in web reseources 