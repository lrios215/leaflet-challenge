# Leaflet Homework - Visualizing Data with Leaflet

## Background

![1-Logo](images/1-Logo.png)

The United States Geological Survey (USGS) is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. 

The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

This map utilizes the [Leaflet open-source JavaScriptlibrary](https://leafletjs.com/), html, JavaScript, and CSS.


### Level 1: Basic Visualization

1. **Data**

   ![USGS Earthquake Data](images/USGS_data.png)

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes. The [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) was used to select a dataset.

   [Dataset Selected: Past 7 Days, M2.5+ Earthquakes (updated every minute)](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/2.5_week.geojson)

   ![JSON](images/JSON.png) 


2. **Map Visualization of the Data**

    ![JSON](images/map.png) 
   
   A map was created using Leaflet that plots all of the earthquakes from the above mentioned data set based on their longitude and latitude.

   * The data markers reflects: 
        * The magnitude of the earthquake by their size 
        * The depth of the earthquake by color
        * Earthquakes with higher magnitudes appear larger and earthquakes with greater depth appear darker in color

   * Popups that provide additional information about the earthquake when a marker is clicked:
        * Specific Location, time and magnitude

   * Legend shows the depth range based by color

- - -
