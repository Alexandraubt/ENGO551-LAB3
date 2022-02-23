# Project 3

ENGO 551 - Alexandra Urbieta Torres

# The objectives of this lab were:
1. To gain experience with Mapbox Vector Tiles and Mapbox Studio
2. To Design a visually appealing map layer
3. Integrate a vector tileset to an existing GeoWeb application


## STEP 1
Download the 2017 Traffic Incidentes data set from the City of Calgary as a CSV file.

## STEP 2
Using Mapbox I costumized a map and add the dataset from part 1 as a layer. I decided to change the componentes colors to a cute-girly-style map with a pink base (unfortunately it doesnt look as good as I thought), and light colors for the rest of features. The layer is a red circle with a radios of 3px, an opacity of 1, a blur of 0, and a black strock color. 

## STEP 3
I used my code from lab 2, and I added the two new layers created in Mapbox (https://api.mapbox.com/styles/v1/YOUR_USERNAME/YOUR_STYLE_ID/tiles/256/{z}/{x}/{y}?access_token=YOUR_MAPBOX_ACCESS_TOKEN) , my map from Mapbox with the layer and without the layer. I also kept the map from lab 2. Because I used my lab 2, the building permits are still available in each of the 3 layers.
.

### Built With
* [LeafLet](https://leafletjs.com/)
* [MapBox](https://geojson.org/)


### References
* ENGO551 - Lab 2 Assignment
* https://docs.mapbox.com/mapbox.js/example/v1.0.0/leaflet-studio-style/
* Github user Project 2https://github.com/samrknight12/project2

