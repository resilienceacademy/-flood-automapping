## Automating Global Geospatial Data Set Analysis
### Visualizing flood disasters in the cities of the Global South

This code will turn raster data into an interactive local kepler.gl web map displaying the extent of flooding events and its effects on the local population and infrastructure.

The script is used as the research method in the Master's thesis of Ohto Nygren for the Department of Geography at the University of Turku, Finland.

Flood data has been provided by the new space company ICEYE and the world settlement footprint (WSF) population data that was used was provided by the German Aerospace Agency (DLR). The script has been optimized for these datasets, but similar data can most likely be used with the script.

Running the script will produce an interactive map as a .html file, a bar chart of the affected population by flood classes, and print information on the number of buildings inundated, and of essential services (hospitals and pharmacies) inundated.

The OSMnx module is used to pull data from OpenStreetMap (OSM) to get estimations of inundated buildings, with an emphasis on hospitals and pharmacies.

Estimations provided by the script are not completely accurate due to the lack of mapped OSM data, but flood depths captured by ICEYE's SAR satellites are very accurate and the population data created by the DLR is very accurate for a global dataset. 

The main idea is to provide quick first estimations via Python automatization of the extent of flood damage and the number of people affected by a flooding event to first responders and international humanitarian aid.



Conctact information for further questions:

Ohto Nygren

omnygr@utu.fi

MSc student in geography

University of Turku

Finland
