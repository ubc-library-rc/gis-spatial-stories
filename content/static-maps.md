---
layout: default
title: Static Maps
nav_order: 5
parent: Determining Output
---

# Static Maps
{: .no_toc}

There are a variety of spatial stories you can tell with a static map. Static maps can provide geographic reference for your story, such as locating your research area or the countries visited by a historical figure. Static maps can show geophysical features such as mountains, rivers, or coastline, or show infrastructural networks, buildings, and aerial imagery. Static maps can also visualize the results of spatial analysis. This page describes two kinds of static maps: **reference maps** and **thematic maps**, and provides illustrative examples for each. 

<details open markdown="block">
  <summary>
    On this page:
  </summary>
  {: .text-delta }
 - TOC
{:toc}
</details>

----

## Reference Maps
Reference maps are useful to show the lay of the land, such as the geographic context surrounding your research area or area of interest. 

Reference maps can be as simple as a drop pin location, with an optional inset. Insets either zoom-in on a select area in order to show it in greater detail, or they zoom-out to put a select area into wider geographical context.
<img src="./reference/jr-park.jpeg" style="width:100%;">

Reference maps can display a single data layer, such as Vancouver Parks.
<img src="./reference/reference-example.jpeg" style="width:100%">

Or, reference maps can simply show the geography or infrastructure in a specific area.

<img src="./reference/myosm-granville-bridge.png" style="width:48.5%"><img src="./reference/myosm-local-area-map.png" style="width:50%">


<img width="100%" src="https://api.mapbox.com/styles/v1/mapbox/satellite-v9/static/-123.1344691167005, 49.27065219090755,14.75,0,0/600x300@2x?attribution=true&logo=true&access_token=pk.eyJ1IjoibGlseWRlbWV0IiwiYSI6ImNsazcyZ25zdjAzemwzcm1ydnNybmkwb2EifQ.ggoNMtZ32x8wK-tGYFOCDg" alt="Mapbox map of -123.1344691167005, 49.27065219090755"/>
    
<br>

See [Vancouver's bike map](https://vancouver.ca/files/cov/map-cycling-vancouver.pdf) for a handy reference guide to all the bike-friendly streets around the city. 
<!-- <img src="./images/map-cycling-vancouver.png" style="width:100%"> -->
 

----
    
  
## Thematic Maps & Spatial Analysis
Writes _Statistics Canada_: "A thematic map shows the spatial distribution of one or more specific data themes for standard geographic areas." [Thematic maps](https://en.wikipedia.org/wiki/Thematic_map) render the results of **Spatial anlaysis**. 

 >>  **Spatial analysis** is the process of manipulating spatial information to extract new information and meaning from the original data. Usually spatial analysis is carried out with a Geographic Information System (GIS). A GIS usually provides spatial analysis tools for calculating feature statistics and carrying out geoprocessing activities as data interpolation. -- [QGIS](https://docs.qgis.org/2.18/en/docs/gentle_gis_introduction/spatial_analysis_interpolation.html#:~:text=Overview,Geographic%20Information%20System%20(GIS).)
 
  If you have spatial questions you want to explore with your data, you'll likely need to perform some kind of spatial analysis within a GIS. There are a couple GIS applications out there that can be downloaded from the web directly to your personal computer; these will be further described in **Assembling Resources**. Remember, you can alway email `library.gis@ubc.ca` or [book a consult](https://libcal.library.ubc.ca/appointments/research_commons#s-lc-public-pt) with the Research Commons' GIS Team if you are not sure what tools/software your project will require. 

  OK. Let's take a look at some examples of thematic maps. You can read more about the pros and cons of different kinds of thematic maps [here](https://mapscaping.com/what-is-a-thematic-map/). 

    

### Choropleth Maps

[Choropleth maps](https://en.wikipedia.org/wiki/Choropleth_map) symbolize data by a color gradient representing the magnitude, intensity, or occurrence of values relative to bounded areas such as neighborhoods, municipalities, our countries. Axis Maps has a great introduction to [choropleth maps](https://www.axismaps.com/guide/choropleth). Showing two variables at once? try making a [bivariate choropleth map](https://bnhr.xyz/2019/09/15/bivariate-choropleths-in-qgis.html) in QGIS.

<img src="./reference/choropleth-example.jpeg" style="width:100%">



If you have a substantial amount of time, you can create elaborate, aesthetic maps using both a GIS and illustration software. The following map was made by the workshop author, Lily Demet, for the UBC Disaster Resilience Research Network Report. 
<img src="./reference/choropleth-example-lilydemet.png" style="width:100%">

<br>


### Heatmap
<!-- > or distance to a library or community center -->
A heatmap visualizes point data by occurrences. 
<img src="./reference/heatmap-example2.jpeg" style="width:100%">



### Proportional Symbol map 
[Proportional symbol maps](https://www.axismaps.com/guide/proportional-symbols) are maps with symbols whose size corresponds to total numbers in different areas, such as population or number of earthquakes per year. [You can also make multiple variable proportional symbol maps](https://www.axismaps.com/guide/proportional-symbols). Proportional symbol maps can be made in a GIS, or in an illustration software. 


### Cartogram and Dot Density Maps

[Dot density maps](http://www.axismaps.com.s3-website-us-east-1.amazonaws.com/guide/univariate/dot-density/) and [cartogram maps](https://en.wikipedia.org/wiki/Cartogram) are other thematic options. If you're using QGIS as a mapping software, you'll need to install a [plugin](https://plugins.qgis.org/plugins/) to create either. 



<br>
<br>

