# Leafless: An Indicator for Fallen Leaves on NYC Streets
* Presented during NYC Open Data Week, March 2019.
* An algorithm that predicts the location of “hotspots” around the city that are more susceptible to street flooding and accidents as a result of fallen leaves.

### An example of fallen leaves that would contribute to clogged catch basins
![picture alt](https://torontodrainservice.com/wp-content/uploads/2016/10/Leaves05-1024x310.jpg "An example of fallen leaves.") 

## Built With
* [Pandas](https://pandas.pydata.org/) - Used to clean up & organize data.
* [Sodapy/Socrata](https://dev.socrata.com/consumers/getting-started.html) - API access to NYC Open Data Collections
* [GeoTable](https://pypi.org/project/geotable/) - Used to handle spatial data
* [Wikipedia API](https://pypi.org/project/geotable/) - Scrape Wikipedia Articles to sort trees by type (coniferous, deciduous, etc)
* [Folium](https://pypi.org/project/folium/) - Renders heatmap from data

## Demo
[Heatmap Generated](https://sites.google.com/view/leaflessnyc/zipcodes/11419 "Heatmap Generated")<br>
[Tool & Choropleth Map](https://crosscompute.com/t/2Mdo29l4KCuHIRw4ViR8ZHvHU8YgdwXf "Tool")
