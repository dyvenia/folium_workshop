# folium_workshop

## Useful links:
https://python-visualization.github.io/folium/index.html

https://www.youtube.com/watch?v=t9Ed5QyO7qY&ab_channel=RyanNoonan

## The purpose

This workshop has been organized to provide an overview of the Python ```folium``` library. The focus is on getting the idea of how it works and what are the possibilites. There are no advanced maps presented as this topic is too extensive to cover in a 60 minute meeting.

## How to prepare for the workshop
1. Update your ```viadot``` by going to ```viadot\docker``` and run ```update.sh``` file. After successful update run ```run.sh```.
2. Clone this repo to your viadot folder ```git clone https://github.com/dyvenia/folium_workshop.git```
3. Open the repo in ```localhost:9000```

## Working with folium

Make sure that the package is installed by running ```!pip install folium```. After it's installed, ```import folium``` and ```from folium import plugins``` into your project. The functions and classes used in this workshop include:
- ```folium.Map()```
- ```folium.Marker()```
- ```folium.CircleMarker()```
- ```folium.FeatureGroup()```
- ```folium.plugins.FeatureGroupSubGroup()```
- ```folium.map.LayerControl()```
- ```folium.Icon()```
- ```add_to()```
- ```add_child()```

You will also need to ```import pandas as pd```. The majority of work will be done using Python's native functions.
