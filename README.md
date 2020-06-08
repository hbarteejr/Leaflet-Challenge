# Leaflet-Challenge

In this challenge, the U.S. Geological Survey is interested in building a new set of tools that will allow them to visualize their earthquake data. 

They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. 

In this challenge, their hope is to be able to visualize their data which will allow them to better educate the public and other government organizations (and hopefully secure more funding...) on issues facing our planet.


Level 1: Basic Visualization

![2-BasicMap](Images/2-BasicMap.png)

As a follow-up, the first task is to visualize an earthquake data set.

1.  **Get your data set**

   ![3-Data](Images/3-Data.png)

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and pick a data set to visualize. When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. You will be using the URL of this JSON to pull in the data for our visualization.

   ![4-JSON](Images/4-JSON.png)

2. **Import & Visualize the Data**

   Create a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.

   * Your data markers should reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes should appear larger and darker in color.
   * Include popups that provide additional information about the earthquake when a marker is clicked.
   * Create a legend that will provide context for your map data.
   * Your visualization should look something like the map above.


### Assessment

The final product will be assessed on the following metrics:

* Completion of assigned tasks

* Visual appearance

* Professionalism



