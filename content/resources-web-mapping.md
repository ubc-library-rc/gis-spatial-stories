---
layout: default
title: Web Mapping
nav_order: 3
parent: Assembling Resources
---
# Resources for web mapping 
{: .no_toc}

At a glance, 
- what it is; useful for xyz
- difficulty/learning curve
- access/ open source or proprietary 
for all, give 
- examples (more than in determine output section?)

Resources
- links to download tool
- links to task specific plugins
- links to tutorials and demos 

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
Leaflet is a set of instructions that your web browser or mobile device uses to display maps and let you interact with them. For example, when you double click your mouse on a map, leaflet tells your browser to zoom in. Leaflet defines the style of your map and includes things like zoom controls, attribution links, pop-ups, colors for markers and more. Leaflet is made up of only 38kb of Javascript, so it is really fast and lightweight - meaning browsers don’t have to work very hard to load it. Leaflet is open source, free, and hugely customizable. And, because of this, Leaflet is widely used. There are lots of alternatives to Leaflet, like for example Google Maps, which you need an API key to use.

Leaflet consists of JavaScript and CSS code libraries which power the ways your web browser interprets and interacts with geospatial data & displays colors and style. For instance, when you double click a map to zoom in, Leaflet is at work. When you add data to your map, Leaflet assigns it a default color. And because Leaflet is open-source, the code is hugely customizable and extensible. This means you can re-mix the code all you want — which you will do in this workshop. [Here are some examples](https://leafletjs.com/plugins.html) of Leaflet-based plugins to give you some idea of the variety of added functionality that comes from the community of developers.



- leaflet you can [change the CRS](https://leafletjs.com/reference.html#crs) whereas in Mapbox, always wgs 84 web mercator. 

#### Leaflet Advantages  ⇡
{: .no_toc}

#### Leaflet Disadvantages ⇣
{: .no_toc}

#### Resources for working with Leaflet
{: .no_toc}
- [Intro to Leaflet](https://ubc-library-rc.github.io/gis-intro-leaflet/) workshop
#### Plugins/tutorials for basic thematic mapping
{: .no_toc}
- [Heatmaps with Leaflet](https://leafletjs.com/plugins.html#heatmaps)
- [Clustering](https://github.com/Leaflet/Leaflet.markercluster)
> - [see example](https://leaflet.github.io/Leaflet.markercluster/example/marker-clustering-realworld.388.html)

#### code for making dashboard / etc. 
{: .no_toc}
- [adding side panels/menus to leaflet map](https://unbam.github.io/Leaflet.SlideMenu/)
- [another side bar example](https://github.com/noerw/leaflet-sidebar-v2)
    > - [see demo here](https://noerw.github.io/leaflet-sidebar-v2/examples/)

- [leaflet marker cluster](https://github.com/leaflet/Leaflet.markercluster)

- [ overlay layers control](https://leafletjs.com/examples/layers-control/)
- time sldier

- [plugins for data vizualization](https://leafletjs.com/plugins.html#dataviz)

- [Leaflet Tutorials](https://leafletjs.com/examples.html)
- UBC Research Commons' [Intro to Leaflet Workshop](https://ubc-library-rc.github.io/gis-intro-leaflet/)

Plugins --> extended functionality - makes leaflet hugely customizable
- [Leaflet plugin database](https://leafletjs.com/plugins.html)
- EG create a [side panel](https://github.com/maxwell-ilai/Leaflet.SidePanel) (scroll down to see [example](https://maxwell-ilai.github.io/Leaflet.SidePanel/examples/))

----

## Mapbox
[Mapbox](https://www.mapbox.com/) is a robust Geospatial Software As A Service (saas) for developers, and includes products such as toolkits for mobile app development, navigation, web maps, and data management. Mapbox's service model is based on a paid subscription, but they offer a free service tier for those interested in using Mapbox products for learning. You will be asked to put in credit card information, however. If this is your first time hearing about Mapbox, [How Mapbox Works](https://docs.mapbox.com/help/getting-started/) provides a great introduction.

Note you can make maps with code or without. custom basemap styles etc. 
Fancier leaflet... maybe best to just do leaflet. 


#### Mapbox Advantages  ⇡
{: .no_toc}

#### Mapbox Disadvantages ⇣
{: .no_toc}

#### Resources for working with Mapbox
{: .no_toc}

- UBC Research Commons' [Intro to Mapbox](https://ubc-library-rc.github.io/intro-mapbox/) workshop
- [Intro to mapbox studio]
- [Choropleth maps with Mapbox](https://labs.mapbox.com/education/thematic-map-types/choropleth/)
- [Heatmaps with Mapbox Studio](https://docs.mapbox.com/help/tutorials/studio-heatmap-tutorial/)
- [Dot Density maps with Mapbox](https://labs.mapbox.com/education/thematic-map-types/dot-density/)
- [Graduated Symbol maps with Mapbox](https://labs.mapbox.com/education/thematic-map-types/graduated-points/)

----
## QGIS to Web
- QGIS plugin for turning your qgis map into an interactive webmap powered by leaflet
- will need somewhere to store map --> github etc. 

could include example of qgis to web map under resources.  

embed example.... 

----
## ArcGIS Online


#### ArcGIS Online Advantages  ⇡
{: .no_toc}

#### ArcGIS Online Disadvantages ⇣
{: .no_toc}

----

## Google Maps 

#### Google Maps Advantages  ⇡
{: .no_toc}
- easy, straightforward, free


#### Google Maps Disadvantages ⇣
{: .no_toc}

----
## Felt
what its good for 

[felt](https://felt.com/)
has a free tier

- [see gallary](https://felt.com/gallery)
- [examples](https://felt.com/map/Baltimore-City-Proposed-Land-Use-April-2024-DEElrNXBRICZ3XTKtmCYKD?loc=39.34342,-76.63756,13.9z)

----
## map libre
https://maplibre.org/


---- 

## uMap
[uMap](https://umap.openstreetmap.fr/en/) "uMap lets you create maps with OpenStreetMap layers in a minute and embed them in your site." is open source, free to use. can add data layers.