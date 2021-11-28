<p align="center">
  <img src="https://github.com/KEGANCP/Mapping_Earthquakes/blob/main/Images/earthquake.png" alt="HEADER"/>
</p>

----
### Project Overview
I have been tasked by The Disaster Reporting Network to generate an interactive map to populate recent earthquake data. My end goal was to allow 3 different map styles, while also having providing the viewer the option to view or hide Tectonic Plates, Earthquakes, and Major Earthquakes.
This was achieved by utilizing:
- Javascript
-  D3
-  Mapbox
-  Leaflet

----
### Map Features
The below shows the end result in a satellite view, with tectonic plates, earthquakes, and major earthquakes selected.

<p align="center">
  <img src="https://github.com/KEGANCP/Mapping_Earthquakes/blob/main/Images/Sample.png" alt="sample"/>
</p>


The below images show both the selectable options to modify your view, as well as the legend to identify the earthquakes intensity.

Map Options             |  Map Legend
:-------------------------:|:-------------------------:
![](https://github.com/KEGANCP/Mapping_Earthquakes/blob/main/Images/options.png)  |  ![](https://github.com/KEGANCP/Mapping_Earthquakes/blob/main/Images/legends.png)

----
### Project Summary
I utilized JavaScript and the D3.js library to identify our coordinates as well as the magnitudes of the earthquakes from the GeoJSON data. The Leaflet library was used to plot the data on a Mapbox map via an API request to generate the final view.
