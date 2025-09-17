---
layout: default
title: Web Mapping
nav_order: 3
parent: Assembling Resources
---
# Resources for web mapping 
{: .no_toc}
This page inventories and evaluates a variety of platforms, tools, and resources for web mapping. 

See our newly redeveloped [Webmapping Workshop](https://ubc-library-rc.github.io/gis-intro-leaflet/content/webmapping-tools.html) for further documentation on many of the following platforms. 

<details open markdown="block">
  <summary>
    On this page:
  </summary>
  {: .text-delta }
 - TOC
{:toc}
</details>

----


## Google MyMaps 

We recommend Google Maps for its Google MyMaps service *only*. With Google MyMaps, you create simple maps with drop pin locations or imported data layers, like the below map: 
<iframe src="https://www.google.com/maps/d/embed?mid=13jisTC20ztRT93EJS0u_6u4_lzvEehk&ehbc=2E312F" width="640" height="480"></iframe>


While the Google Maps Platform offers a panoply of mapping tools including [dynamic maps](https://mapsplatform.google.com/maps-products/dynamic-maps/), you must be very careful about surreptitious charges. For example, while the [embed maps API](https://developers.google.com/maps/documentation/embed/get-started?hl=en) is free with unlimited usage, you must sign up for Google Cloud. Google Cloud is only free for 90 days then will charge you $200 monthly. In our opinion, it is recommended to invest your time and energy in learning a free and open-source option like uMap or Leaflet. 

See our [Google MyMaps demo] (https://ubc-library-rc.github.io/gis-intro-leaflet/content/mymaps.html) in our webmapping workshop. 

----

## uMap
[uMap](https://umap.openstreetmap.fr/en/) is a free and open-source platform that allows you to create webmaps using OpenStreetMap (OSM) data. You can then embed these maps into a website, or simply share the link with collaborators and audiences. You can choose from a variety of basemaps, and even upload and add data layers of your own! uMap is very easy to use, but has little room for customization. It is an entirely web-based interface and requires no prior expertise. 

The below map was created in 5 minutes using data downloaded from Vancouver [open data portal](https://opendata.vancouver.ca/explore/dataset/parks-polygon-representation/information/). See our [uMap demo] (https://ubc-library-rc.github.io/gis-intro-leaflet/content/umap.html) in our webmapping workshop. 


<iframe width="100%" height="500px" frameborder="0" allowfullscreen allow="geolocation" src="//umap.openstreetmap.fr/en/map/vancouver-parks_1219886?scaleControl=false&miniMap=false&scrollWheelZoom=false&zoomControl=true&editMode=disabled&moreControl=true&searchControl=null&tilelayersControl=null&embedControl=null&datalayersControl=true&onLoadPanel=none&captionBar=false&captionMenus=true#12/49.2605/-123.0997"></iframe><p><a href="//umap.openstreetmap.fr/en/map/vancouver-parks_1219886?scaleControl=false&miniMap=false&scrollWheelZoom=true&zoomControl=true&editMode=disabled&moreControl=true&searchControl=null&tilelayersControl=null&embedControl=null&datalayersControl=true&onLoadPanel=none&captionBar=false&captionMenus=true#12/49.2605/-123.0997">See full screen</a></p>

<!-- 
<iframe src="http://u.osmfr.org/m/1219886/" style="width:100%; height:500px"></iframe> -->


----

## Leaflet
[Leaflet](https://leafletjs.com/) consists of JavaScript and CSS code libraries which power the ways your web browser interprets and interacts with geospatial data & displays colors and style. For instance, when you double click a map to zoom in, Leaflet is at work. When you add data to your map, Leaflet assigns it a default color. Leaflet is made up of only 38kb of Javascript, so it is really fast and lightweight - meaning browsers don’t have to work very hard to load it. 

You can download some [boilerplate code](./leaflet-boilerplate.zip) here and play around with it in a code editor. 


> #### Leaflet Advantages  ⇡
> {: .no_toc}
> - Leaflet is free and open source. For this reason, Leaflet is widely used. 
- As an open-source code library, Leaflet is hugely customizable. This means you can re-mix the code all you want. 
> - Leaflet is beginner friendly, though you do need to interact with code in order to build your map.
> - Hugely customizable. Leaflet-based plugins to give you some idea of the variety of added functionality that comes from the community of developers. 
> - In Leaflet, you can [change the CRS](https://leafletjs.com/reference.html#crs) of your map whereas the projection is set in Google Maps and Mapbox. 

> #### Leaflet Disadvantages ⇣
> {: .no_toc}
> - You'll need to work with code in a code editor. This can introduce a semi-steep learning curve, but you can truly create a basic webmap in a few hours with no prior knowledge. 
> - You'll need a place to store your map and map data. Github can work. Think about how you'll be displaying your end product. Will it be embedded on a website? 
<!--could do a tutorial thats like lets make a map and add data to github and make github page-->

#### Resources for working with Leaflet
{: .no_toc}
- UBC Research Commons' NEWLY REVISED [webmapping workshop](https://ubc-library-rc.github.io/gis-intro-leaflet/)!!!

- [Leaflet Tutorials](https://leafletjs.com/examples.html) for getting started
- [Plugins](https://leafletjs.com/plugins.html) offer extended functionality, making leaflet hugely customizable. Below are some plugins to give you some idea of the variety of added functionality that comes from the community of developers. 
- [Heatmaps with Leaflet](https://leafletjs.com/plugins.html#heatmaps)
- [Clustering](https://github.com/Leaflet/Leaflet.markercluster), see this [example](https://leaflet.github.io/Leaflet.markercluster/example/marker-clustering-realworld.388.html)

#### Code/documentation for making dashboards components  
{: .no_toc}
- [Adding side panels/menus to leaflet map](https://unbam.github.io/Leaflet.SlideMenu/)
- [Another side bar example](https://github.com/noerw/leaflet-sidebar-v2); (see demo [here](https://noerw.github.io/leaflet-sidebar-v2/examples/))
- [Leaflet marker cluster](https://github.com/leaflet/Leaflet.markercluster)
- [Overlay layers control](https://leafletjs.com/examples/layers-control/)
- Create a [side panel](https://github.com/maxwell-ilai/Leaflet.SidePanel) (scroll down to see [example](https://maxwell-ilai.github.io/Leaflet.SidePanel/examples/))

The below maps displayed earlier on in this workshop were all made using leaflet:

<iframe src="./reference/leaflet-reference-map.html" style="width:90%; height:450px; border:none;"> </iframe>

<iframe src="./reference/leaflet-choropleth-map.html" style="width:90%; height:400px; border:none;"> </iframe>

<iframe src="./reference/leaflet-proportional-symbol-map.html" style="width:90%; height:450px; border:none; "></iframe>

<iframe src="./reference/leaflet-cluster-map.html" style="width:90%; height:450px; border:none;"> </iframe>

----

## Mapbox
[Mapbox](https://www.mapbox.com/) is a robust Geospatial **S**oftware **A**s **A** **S**ervice (saas) for developers, and includes products such as toolkits for mobile app development, navigation, web maps, and data management. Mapbox's service model is based on a paid subscription, but they offer a free service tier for those interested in using Mapbox products for learning. You will be asked to put in credit card information, however.  If this is your first time hearing about Mapbox, *[How Mapbox Works](https://docs.mapbox.com/help/getting-started/)* provides a great introduction.

> #### Mapbox Advantages  ⇡
> {: .no_toc}
> - Platform for custom styling basemaps
> - Variety of different services, including both code and web-based graphical user interface for web mapping

> #### Mapbox Disadvantages ⇣
> {: .no_toc}
> - Mapbox is proprietary, and the functions are not transposable between other webmapping libraries like Leaflet
> - The Free Tier has limitations that might be of concern to you if you intend to make a map that will be widely viewed and cited
> - Though you can make maps in Mapbox Studio, developing more custom webmaps requires working with code. Even then, Leaflet can often be more customizable because it is open-source and there is more code out there to draw from. 

#### Resources for working with Mapbox
{: .no_toc}
- UBC Research Commons' [Intro to webmapping with Mapbox](https://ubc-library-rc.github.io/intro-mapbox/) workshop
- [Intro to Mapbox studio](https://docs.mapbox.com/studio-manual/guides/)
- [Choropleth maps with Mapbox](https://labs.mapbox.com/education/thematic-map-types/choropleth/)
- [Heatmaps with Mapbox Studio](https://docs.mapbox.com/help/tutorials/studio-heatmap-tutorial/)
- [Dot Density maps with Mapbox](https://labs.mapbox.com/education/thematic-map-types/dot-density/)
- [Graduated Symbol maps with Mapbox](https://labs.mapbox.com/education/thematic-map-types/graduated-points/)


Below is an example of a cluster map made with mapbox:

<iframe src="./reference/mapbox-cluster-map.html" style="width:90%; height:400px; border:none; "></iframe>

----

## Jawg 

With [Jawg](https://www.jawg.io/en/), you can create simple reference maps powered by leaflet with just a few clicks. No tinkering, no coding, just copy paste your new map into a website! Jawg has a handful of [basemaps](https://www.jawg.io/en/maps/) to choose from, and you can even create your own style. The free tier offers quite a lot and is likely enough to get you started. If you want your webmap to stand alone rather than be embedded in a website, look into GitHub Pages. The Research Common's workshop website on [git and github](https://ubc-library-rc.github.io/intro-git/content/04_github.html) may be helpful to get started. 

<iframe src="./reference/jawg-map.html" style="width:90%; height:450px; border:none;"> </iframe>

----
## Map Libre
If you are already code savvy, [MapLibre](https://maplibre.org/) may be of interest to you. In their own words, 
> MapLibre GL JS is an open-source library for publishing maps on your websites or webview based apps. Fast displaying of maps is possible thanks to GPU-accelerated vector tile rendering.

> It originated as an open-source fork of mapbox-gl-js, before their switch to a non-OSS license in December 2020. The library's initial versions (1.x) were intended to be a drop-in replacement for the Mapbox’s OSS version (1.x) with additional functionality, but have evolved a lot since then.

Scroll down on [this page](https://maplibre.org/maplibre-gl-js/docs/) for more information, or view their [Github documentation](https://github.com/maplibre/maplibre-gl-js).

----
## QGIS --> Web

If you're familiar with QGIS, there's actually a nifty plugin for turning your QGIS map into an interactive webmap, either powered by Leaflet or OpenLayers. This plugin is aptly called [qgis2web](https://plugins.qgis.org/plugins/qgis2web/). You just install the plugin, and then ensure your Field visibilities are set under Layer Properties. However, you will need somewhere to store your map and map data, such as Github or a local server. Below is an example qgis2web made map created by the workshop author for BC Disaster Resilience Research Network:
  <iframe src="./reference/qgis2web/index.html" style="width:100%; height:600px;"></iframe>

<!-- [interactive filters](https://digital-geography.com/qgis2web-with-interactive-filters/) -->

See the Research Common's [workshop on QGIS Plugins](https://ubc-library-rc.github.io/gis-plugins-qgis/) for a guided tutorial on how to not only make a webmap using qgis2web, but host it online. 

----
## ArcGIS Online
[ArcGIS Online](https://www.arcgis.com/index.html) or (AGOL) is Esri's online platform for making dynamic and interactive maps. If you are faculty or student at UBC, you can learn more about obtaining access [here](https://gis.ubc.ca/software/#:~:text=FOR%20STUDENT%20PERSONAL%20COMPUTERS&text=This%20%2420%20license%20includes%20ArcGIS,reduced%20cost%20is%20also%20available.&text=This%20is%20a%20non%2Drefundable,installed%20on%20personal%20computers%20only.).

#### ArcGIS Online Advantages  ⇡
{: .no_toc}
> - Allows you to load and save data online, as well as create dynamic maps with customizable basemaps, popups, and interaction

#### ArcGIS Online Disadvantages ⇣
{: .no_toc}
> - ArcGIS Online is proprietary, meaning it is not free to use
> - Licensing is a hassle, and collaboration can only occur between people who both own an active license

----
## Felt
[Felt](https://felt.com/) is a web-based platform for creating aesthetic, interactive maps and dashboards with your data. They offer a free tier that allows you to make and share unlimited webmaps, as well as automatic 14-day free trial of middle tier. 
Checkout their [gallary](https://felt.com/gallery) to get inspired by their [examples](https://felt.com/map/Baltimore-City-Proposed-Land-Use-April-2024-DEElrNXBRICZ3XTKtmCYKD?loc=39.34342,-76.63756,13.9z). 

----

## Map tiles
[Map tiles](https://ubc-library-rc.github.io/gis-intro-leaflet/content/leaflet-basemap.html) are squares of geographic data that are loaded to your frame of view whenever you zoom or pan your map. Each tile is 256px by 256px (traditionally a .png image at roughly 20-40kb each), making them quick to load over an internet connection. These tiles provide a geographic reference for other data layers that you might add later (we’ll get to that in a minute). 

There are some useful map tile services you should know of:
- [Maptiler](https://www.maptiler.com/data/) 
- [Open Map Tiles](https://openmaptiles.org/docs/style/maputnik/) offers open-source maps made for self-hosting, including free open street map vector tiles
- [Basemap providers](https://leaflet-extras.github.io/leaflet-providers/preview/) for leaflet maps. You'll notice some maps require an API key or access token to use. Often you can create a free account on any of these platforms, like [Jawg maps](https://www.jawg.io/en/), and then use there basemaps. 
- Stamen maps recently moved to [Stadia Maps](https://stadiamaps.com/). If you want to use their maps you just have to make an account to get access now
