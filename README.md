# Leafless: An Indicator for Fallen Leaves on NYC Streets
* Presented during NYC Open Data Week, March 2019.
* An algorithm that predicts the location of "hotspots” around the city that are more susceptible to street flooding and accidents as a result of fallen leaves.

### An example of fallen leaves that would contribute to clogged catch basins
![picture alt](https://torontodrainservice.com/wp-content/uploads/2016/10/Leaves05-1024x310.jpg "An example of fallen leaves.") 
## How We Built It
* Using the 2015 Street Tree Census, this tool calculates an individual “risk” for each tree based on its dimensions, species, and health.
* Additional information from the 311 Service Request dataset about clogged catch basins over the last 10 years are also used in calculating the riskiness of a tree based on the locations of nearby catch basins.



## Tools
* [Pandas](https://pandas.pydata.org/) - Used to clean up & organize data.
* [Sodapy/Socrata](https://dev.socrata.com/consumers/getting-started.html) - API access to NYC Open Data Collections
* [GeoTable](https://pypi.org/project/geotable/) - Used to handle spatial data
* [Wikipedia API](https://pypi.org/project/geotable/) - Scrape Wikipedia Articles to sort trees by type (coniferous, deciduous, etc)
* [Folium](https://pypi.org/project/folium/) - Renders heatmap from data

## Demo
[Heatmap Generated](https://sites.google.com/view/leaflessnyc/zipcodes/11419 "Heatmap Generated")<br>
[Tool & Choropleth Map](https://crosscompute.com/t/2Mdo29l4KCuHIRw4ViR8ZHvHU8YgdwXf "Tool")

#### The result is a choropleth map that calculates the "risk" of each city block.
![picture alt](https://github.com/naiemg/Leafless-Fallen-Leaves-Indicator/blob/master/Media/choropleth.png "Choropleth Generated")

#### A heatmap highlights specific "hotspots" that are more directly affected by fallen leaves.
![picture alt](https://github.com/naiemg/Leafless-Fallen-Leaves-Indicator/blob/master/Media/heatmap.png "Heatmap Generated") 

## About the Team
Leafless is a project by team Data Ninjas (Naiem Gafar, Alexander Tenf, Pablo Tenf, and Arthur Korchkov) of the NYC Open Data Student Showcase program. A special thanks to the [Tech Incubator at CUNY, Queens College](https://techincubatorqc.com/ "Link to TIQC"), [Crosscompute](https://crosscompute.com "Link to Crosscompute"), and all of the mentors who have provided exceptional feedback and resources to the team.

## What's next for Leafless
* Improve accuracy by incorporating weather & wind data
* Compatibility with NYC Department of Sanitation trucks to ensure live time tracking of clean-up efforts

