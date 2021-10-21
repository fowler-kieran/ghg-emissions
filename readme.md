## Project: Proportional Symbol Map of State-level GHG Emissions

### Description

This project was designed to create a webmap that displays the per-capita GHG emissions for each U.S. state.

The map uses proportional symbols to display the data, with a minimum radius of 14. The data values range from 9.0 to 109.9 metric tons of CO2 emissions

I gathered the data from the US Energy Information Admisitration and compiled it into a table, along with corresponding state names and central latitude and longitude coordinates.

For interactive purposes, users can hover over each marker to highlight it in a blue color.

All the symbology is displayed using a dark red color (#de2d26), which I found from using the Colorbrewer [application](https://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3).

#### Libraries

- The Javascript library, Leaflet, can be accessed [here](https://leafletjs.com/download.html).
- Ajax, which can be downloaded [here](https://cdnjs.com/libraries/leaflet-ajax).
- jQuery, which can be found [here](https://code.jquery.com/).

#### Data

- Basemap acquired from [Leaflet Providers](https://leaflet-extras.github.io/leaflet-providers/preview/).
- Data gathered from the [US Energy Information Administration](https://www.eia.gov/environment/emissions/state/).
- geoJSON conversion of emissions data from [geojson.io](https://geojson.io/#map=2/20.0/0.0).
