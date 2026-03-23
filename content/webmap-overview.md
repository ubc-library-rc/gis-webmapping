---
layout: default
title: What is a web map?
nav_order: 1
---

# What is a web map? 
{: .no_toc}

 Web maps are dynamic, interactive maps that are hosted on the web and can be shared to others via a link. Web maps are ubiquitous in our everyday: for example, you likely use a web map on your phone to navigate around the city, track an online order, ride, or bus, and check the weather forecast near you. 
 
 Web maps differ from digital maps, which are simply static maps derived from a computer and produced/published/stored in a digital format (such as an image or PDF). (The term "born digital" is often used to describe these kind of maps.) Examples of digital maps include scans of historical maps, or maps embedded online as graphics. 
 
In contrast, **Web maps can be identified based on some key characteristics:**

- **Dynamic scales and content** Web maps are not static images. Different scales display varying levels of detail. For instance, zooming in may reveal information that wasn’t apparent before. For this reason, web maps are not designed for print.
- **Interactive** Web maps are built to be interacted with by an end user, often in order for the user to explore a dataset and learn something. Take for example [Climate Central’s Surging Seas Risk Zone Map](https://ss2.climatecentral.org/#12/40.7298/-74.0070?show=satellite&projections=0-K14_RCP85-SLR&level=5&unit=feet&pois=hide). Or, listen to the radio anywhere in the world with [radio.garden](https://radio.garden/visit/vancouver/Lc5d7EdP). 
- **Display real-time data updates** Web maps are useful for geovisualizing real-time data like weather. Watch the wind blow across the country on [Ventusky](https://www.ventusky.com/?p=43.8;-97.3;5&l=temperature-2m).
- **Often rely on web and mobile technology** For example, Google Maps' navigation algorithm that helps you find directions or search for coffee shops around town. For app builders, web maps might provide a method for routing to locations using a mobile device’s geolocation features. For researchers, they may help communicate important information in an area of study. 


## Examples of webmaps 
The most basic web map is a basemap, contained in a viewbox with controls and an attribution at the bottom. 

<iframe src="./reference/basic-map.html" style="width:100%; height:520px; border:none;"> </iframe>

<br>

Web maps can show a drop-pin location...

<iframe src="./reference/single-point.html" style="width:100%; height:520px; border:none;"> </iframe>

Or display one or more data layers.

<iframe src="https://www.google.com/maps/d/embed?mid=11gHGxEF2Uxx7zbn00htegHybzWBS3ro&ehbc=2E312F&noprof=1" style="width:100%; height:520px; border:none;"></iframe>
<sub>[View in Full Screen](https://www.google.com/maps/d/embed?mid=11gHGxEF2Uxx7zbn00htegHybzWBS3ro&ehbc=2E312F&noprof=1)</sub> 

<br>

<iframe style="width: 100%; height: 520px; border: 0;" allowfullscreen src="//umap.openstreetmap.fr/en/map/toronto-public-art_1377239?scaleControl=false&miniMap=false&scrollWheelZoom=false&zoomControl=true&editMode=disabled&moreControl=true&searchControl=null&tilelayersControl=null&embedControl=null&datalayersControl=true&onLoadPanel=none&captionBar=false&captionMenus=true#11/43.72/-79.42"></iframe>

<br>

Cluster maps... 
<iframe src="./reference/art-and-heritage-clustered.html" style="width:100%; height:520px; border:none;"> </iframe>


### Some other reference web maps out there:

- [Falling Fruit](https://fallingfruit.org/locations/embed?z=10&y=49.24090&x=-483.04568&m=true&t=roadmap&c=forager,freegan&l=false&locale=en) is a foraging map, hosted by Google Maps. Everyday people can anonomysouly upload finds such as a lush patch of blackberries, alleyway lemonbalm, or a plum tree in a yard slated for demolition. 

- [Native-land.ca](https://native-land.ca/) shows Indigenous territories across Turtle Island and around the world. You can search First Nations by territories, languages, or treaties. The map can be overlaid upon a colonial, cartesian basemap. This web map is powered by Mapbox, with basemap tiles from Open Street Map. 

- [Queering the map](https://www.queeringthemap.com/) visualizes anonymized, user-submitted queer experiences around the world. While their basemap used to be Google Maps, it recently changed to Open Street Map. It's unclear what library is powering the interactivity of this web map, but extended documentation is impressively available on [Radical-data's Github](https://github.com/radical-data/queering-the-map). 



So far, all of the above webmap examples have been reference maps. You can also make thematic webmaps, but that is beyond the scope of today's workshop. 




<!-- 
show with each platform. discuss advantages/disadvantes briefly or when we get into it. 

oh, there's also AGOL..... ? different day when we do storymaps? 
Mention narrative mapping will be another day. 
 -->










