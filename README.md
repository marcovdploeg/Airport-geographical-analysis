# Airport-geographical-analysis

This repostory contains code to find out what the optimal placement of a new airport in the Netherlands would be,
based on which fraction of the population is within a certain distance of all the airports.
The result depends on the chosen radius within which an airport is close enough to all people living in a certain municipality.
For three of these radii (10, 30 and 50 km) an html map with the results is saved.
(Note that some of the output in the notebook had to be cleared in order to stay within the allowed file size.)

Applied methods in this script are: data manipulation with pandas, analysis using geopandas, creating maps using folium.

The used datasets can be found at:
- https://www.kaggle.com/datasets/jinbonnie/airport-information
- https://www.nationaalgeoregister.nl/geonetwork/srv/dut/catalog.search#/metadata/6be88637-f10f-44a4-aa5c-fc8c0f857620
- https://www.cbs.nl/nl-nl/maatwerk/2025/10/voorlopige-bevolkingsaantallen-per-gemeente-1-1-2025
