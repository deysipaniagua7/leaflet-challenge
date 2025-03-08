# leaflet-challenge

This is the repository that holds my Module 15 leaflet-challenge.

Module Overview: The module asked us to develop a visualization using USGS data to allow the United States Geological Survey (USGS) to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet. Part 1 was to create an earthquake visualization. Part 2 was to gather and plot more data; however, this portion was optional, and I did not complete it.

For part 1, we had to obtain an earthquake dataset from the USGS GeoJSON Feed page (I chose the “All Earthquakes from the Past 7 days” dataset) and use its URL of the JSON to pull in the data for the visualization. Using Leaflet, we then had to import and create a map that plots all the earthquakes from the dataset based on their longitude and latitude. The data markers had to reflect the magnitude of the earthquake by their size and depth by color. Those with higher magnitude were to be displayed larger and those with greater depths were to appear darker. We then had to include popups to provide additional information about the earthquake when its associated marker is clicked. Finally, we had to create a legend to provide context for the map data.

The main "leaflet-challenge" repo contains an 1) "index.html" file to generate the map, 2) an “Images” folder to guide us, through the challenge and 3) a “static” folder with two subfolders: “css” and “js”. The first subfolder contains a “style” file and the second contains the “logic” file with my JavaScript code.

Please note, I used in-class activities/notes and the following resources to complete the module:

-https://stackoverflow.com/questions/55796506/syntax-to-set-the-color-of-a-circle-using-data

-https://plotly.com/javascript/plotlyjs-function-reference/#plotlyrestyle

-https://leafletjs.com/examples/geojson/

-https://leafletjs.com/examples/layers-control/

-https://leafletjs.com/examples/choropleth/

-https://colorbrewer2.org/#type=sequential&scheme=PuBuGn&n=6

