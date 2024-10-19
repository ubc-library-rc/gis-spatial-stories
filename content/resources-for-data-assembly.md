---
layout: default
title: Data
nav_order: 1
parent: Assembling Resources
---

# Assembling your Data

It's now time to assemble your data. Take a moment to inventory what you have, as well as what you'll need by returning once more to initial project design questions (see worksheet):

> - What data do you have? What data will you need?

> - Whose data is it? Are there any special permissions you need to obtain or access restrictions to be aware of? Note where you are storing your data, any associated licences/attributions, and ensure everyone who needs access has it.

<!-- > - How are you managing and storing your data? Will you and everyone who needs to have access to everything for the duration of this project? -->

> - What format is your data in? (For example, it could be in an excel document or csv, or a collection of images, a text file, a geospatial file such as a shapefile, geoJSON, .tif, xml....) Do you need to convert any of your data into a different format? 
	>> As you work through choosing an appropriate software, it will become clearer whether or not your data's current form is legible to the software you intend to use. There are often ways to convert data between formats. [FME](https://fme.safe.com/) is a good interoperability resource for more complex workflows, and they are generous with free student licenses. 

> - What aspect of your data is spatial? In other words, what is the location/geographical attribute? For example, is it a column of street address? The names of cities? Coordinate pairs?...
<!-- are there any location based attributes?
 (street address, geographic coordinates, city, town, country?) is there a map? (skills: geocoding, georeferencing, projecting) --> -->
<!-- How to determine what's so spatial about your data.... (st addressses, then geocode) (given cities, spatial join to city layer in qgis OR add columns for xy data - copy paste from google maps  )(coordinates, display xy )(draw layer aoi in qgis) this all shows the myriad of ways data can be spatial spatializing data - (geocoding, displaying xy data) data analysis -->

Below are some resources for finding more data or creating your own. disclaimers??

----

## Resources for assembling data 
The data you’ll need depends on your mapping objectives. Maybe you already have data. Maybe you want to create a reference map and all you need is contextual information and the ability to add some labels and markers. Perhaps your research lab is collecting and processing the data for you. Whether your area of interest is local or global, whether your final map will be static, interactive, or simply the results of some spatial analysis… these factors will influence where you look for data. Municipal and federal data repositories are a good place to begin looking for geospatial data. If you have access to a data repository, either through a group you’re working with/for or institutional library for example, reaching out to whoever coordinates on the matter can be useful. You can also begin with a web search and see what is returned. Lastly, in some cases you can make your own data. This is particularly true if you only need a reference point or simple boundary outline. 


## Considerations
Whether you’re performing spatial analysis or making maps for yourself or a client, its important to keep a record of your data sources as you work. You’ll figure out a system that make sense to you. Trial and error a few times. However, The following considerations are useful to note somewhere like a document or notes file as you go.

```
- What is the dataset of and where did you download it from (save a link)
- What is the downloaded file called? Where is it stored on your computer/external storage device?
- Is there a visual data preview such as an interactive web map?
- What attributes are included in the dataset? 
- Who is the dataset published by and is there a contact for questions? 
- What is the dataset's license?
- When was it last updated?
- What formats can the dataset be downloaded in? 
- What projections can the dataset be downloaded in?
```


## Finding [Geospatial data](https://ubc-library-rc.github.io/gis-intro-qgis/content/geospatial-data.html)

Explore UBC Library's compendium of data sources for Canada and the world [HERE](https://guides.library.ubc.ca/gis/datasources)

    
### Municipal and Provincial Data 
- [BC Data](https://catalogue.data.gov.bc.ca/)
- [Administrative and Statistical Boundaries 2021 (e.g., provinces, census divisions, dissemination areas)](https://www12.statcan.gc.ca/census-recensement/2021/geo/sip-pis/boundary-limites/index2021-eng.cfm?year=21)
- [City of Vancouver open data portal](https://opendata.vancouver.ca/pages/home/)
- [Metro Vancouver open data portal](https://open-data-portal-metrovancouver.hub.arcgis.com/)
- [Burnaby open data portal](https://data.burnaby.ca/)
- [Victoria](https://opendata.victoria.ca/) 
- [Guelph](http://data.open.guelph.ca/)
- [Toronto](https://open.toronto.ca/)
- [Kelowna](https://opendata.kelowna.ca/)
- [Kamloops](https://mydata-kamloops.opendata.arcgis.com/)
- [Calgary](https://data.calgary.ca/) 

### Global Census Data 
- [World urbanization](https://population.un.org/wup/DataQuery/)
- [World demographics](https://population.un.org/dataportal/home?df=d7cac223-d504-404f-807a-03d475ad6c63)

### Global Boundary Files
- [Natural Earth data](https://www.naturalearthdata.com/downloads/) 
- [USA TIGER line shapefiles](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html)
- [Earthworks Stanford](https://earthworks.stanford.edu/)
- [The Humanitarian Data Exchange](https://data.humdata.org/dataset)


### Street Network Examples
- [OSM Street Network](https://www.openstreetmap.org/#map=11/49.2465/-123.0908&layers=H) (see [downloading OSM data in QGIS](./osm-downloader.md))
- [canada road network file](https://www12.statcan.gc.ca/census-recensement/2021/geo/sip-pis/rnf-frr/index2021-eng.cfm?year=21)
- [USA Primary Roads](https://catalog.data.gov/dataset/tiger-line-shapefile-2019-nation-u-s-primary-roads-national-shapefile)
- [India Roads (2016)](https://geodata.mit.edu/catalog/stanford-qf525mn4696)
- [EU Major Road Network](https://data.europa.eu/data/datasets/major-road-network?locale=en)

### Climate, Landcover, and Satellite Imagery
- [World Climate Data](https://www.worldclim.org/)
- [World Land Cover](https://data.apps.fao.org/catalog/iso/8cf69f76-1be0-4339-a0b0-18a93c7f4760)
- [World Land Cover (2)](https://viewer.esa-worldcover.org/worldcover/)
- [Places to download free sattelite imagery](https://gisgeography.com/free-satellite-imagery-data-list/)
- [Canada Land Cover](https://natural-resources.canada.ca/maps-tools-publications/satellite-imagery-air-photos/application-development/land-cover/21755)
- [Canada DEM](https://open.canada.ca/data/en/dataset/957782bf-847c-4644-a757-e383c0057995)
- [BC Lidar](https://lidar.gov.bc.ca/pages/download-discovery)

<br>
----

#### Resources to Learn more about Geospatial Data
- [Koerner Library Data Source Guide](https://guides.library.ubc.ca/gis/datasources)
- [gis.ubc.ca/data/](https://gis.ubc.ca/data/)
- [What is geospatial data?](https://ubc-library-rc.github.io/gis-intro-qgis/content/geospatial-data.html)
- [More than you ever wanted to know about GeoJSON - Tom MacWright](https://macwright.org/2015/03/23/geojson-second-bite.html)  
	