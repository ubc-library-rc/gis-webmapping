---
layout: default
title: Introduction
nav_order: 1
---
# Intro to Webmapping
This workshop explores web maps (aka webmaps) and web mapping (aka webmapping). Web maps are a means of dynamically and interactively visualizing geospatial data. Today, you will learn how to create web maps in 2 different manners: 

1. **online**, through platforms such as [uMap](https://umap.openstreetmap.fr/en/) and [Google MyMaps](https://www.google.com/maps/about/mymaps/), and
2. with **coding**, powered by [Leaflet](https://leafletjs.com/).

Each of these methods of web mapping has its advantages and disadvantages which we will discuss. Moreover, while we emphasize that web mapping can be done entirely online without any coding necessary, we believe it important to have a basic understanding of how web maps work. To this end, we will break down the "anatomy" of a web map together in a code editor in order to understand how the various components of a web map work together. By the end of the workshop, you will be equipped with the fundamental knowledge and skills to begin web mapping on your own. 


Below are examples of webmap made with uMap, Google MyMaps, and Leaflet.
<iframe src="./content/reference/leaflet-example.html" style="width:100%; height:520px; border:none;"> </iframe>
<sub>[View in Full Screen](./reference/leaflet-example.html)</sub> 


<br>


<iframe src="https://www.google.com/maps/d/embed?mid=11gHGxEF2Uxx7zbn00htegHybzWBS3ro&ehbc=2E312F&noprof=1" style="width:100%; height:520px; border:none;"></iframe>
<sub>[View in Full Screen](https://www.google.com/maps/d/embed?mid=11gHGxEF2Uxx7zbn00htegHybzWBS3ro&ehbc=2E312F&noprof=1)</sub> 

<br>

<iframe style="width: 100%; height: 520px; border: 0;" allowfullscreen src="//umap.openstreetmap.fr/en/map/toronto-public-art_1377239?scaleControl=false&miniMap=false&scrollWheelZoom=false&zoomControl=true&editMode=disabled&moreControl=true&searchControl=null&tilelayersControl=null&embedControl=null&datalayersControl=true&onLoadPanel=none&captionBar=false&captionMenus=true#11/43.72/-79.42"></iframe>
<!-- 
<p style="font-size:11pt;"><a href="//umap.openstreetmap.fr/en/map/toronto-public-art_1377239?scaleControl=false&miniMap=false&scrollWheelZoom=true&zoomControl=true&editMode=disabled&moreControl=true&searchControl=null&tilelayersControl=null&embedControl=null&datalayersControl=true&onLoadPanel=none&captionBar=false&captionMenus=true#11/43.72/-79.42" target="_blank">View in full screen</a></p> -->
<sub>[See full screen](//umap.openstreetmap.fr/en/map/toronto-public-art_1377239?scaleControl=false&miniMap=false&scrollWheelZoom=true&zoomControl=true&editMode=disabled&moreControl=true&searchControl=null&tilelayersControl=null&embedControl=null&datalayersControl=true&onLoadPanel=none&captionBar=false&captionMenus=true#11/43.72/-79.42)</sub>   

## Audience


## BEFORE THE WORKSHOP
1. Download and **unzip** the workshop data folder to a location on your physical computer, such as Desktop or Downloads.

[Download Data](./webmapping-workshop.zip){: .btn .btn-blue }

2. To make your life easier while viewing or editing code, it's good to use a [source code editor](https://en.wikipedia.org/wiki/Source_code_editor). This workshop will use [Visual Studio Code](https://code.visualstudio.com/download), but other editors like [Notepad++](https://notepad-plus-plus.org/) and [Sublime Text](https://www.sublimetext.com/3) will work similarly. 

3. Create a [uMap](https://umap.openstreetmap.fr/en/) account. If you don't already have a Google account, creating one for the purposes of using MyMaps is optional. 

4. Finally, create a [GitHub](https://github.com/) account. 


### Data
Inside the unzipped `webmapping-workshop` data folder you will see today's data further organized into 2 subfolders relevant to webmapping online and webmapping with Leaflet respectively.

We will webmap using data primarily from the [City of Toronto's open data portal](https://open.toronto.ca/catalogue/). This data is licensed under the [Open Government Licence - Toronto](https://open.toronto.ca/open-data-licence/). This allows us to modify and adapt the data! The following datasets are from the City of Toronto. They have been reformatted to be legible to the various tools and platforms we will work with today. Take a moment to browse the datasets online. 

- [Public Art](https://open.toronto.ca/dataset/public-art/)
- [Heritage Conservation Districts](https://open.toronto.ca/dataset/heritage-conservation-districts/)

<br>

<!-- - [Green Spaces](https://open.toronto.ca/dataset/green-spaces/)
- [City Wards](https://open.toronto.ca/dataset/city-wards/)
- [Regional Municipal Boundary](https://open.toronto.ca/dataset/regional-municipal-boundary/) -->




<br><br>

----
#### GIS Resources at UBC:

- General Informational website for all things UBC GIS: [gis.ubc.ca](http://gis.ubc.ca/)
- Archive of all [Research Commons workshops](https://ubc-library-rc.github.io/)
- Research Commons [Events Calender](https://researchcommons.library.ubc.ca/workshops/)
- Contact UBC Library’s Geospatial team: `library.gis@ubc.ca`
- Schedule a 1:1 consult with the geospatial team [here](https://libcal.library.ubc.ca/appointments/research_commons#s-lc-public-pt)


<p style="margin-top:70px"></p>
<p style="color:grey; font-size:13px">This workshop was authored by <a href="https://geog.ubc.ca/profile/lily-crandall-oral/" target="_blank"> Lily Demet</a> and reviewed by Alex Alisauskas.</p>






