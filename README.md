This is an experiment to visualize correlation between 2016 USA Election and demographic data.

## Visualize data for US election

There is no source for the results to date, so I scrape the NYTimes results, downloading each State webpage per hand and scraping with Pandas.

The individual webpages are in `nytimes_elections_results_states/`.

Some State have no data (see nytimes_files_scraper.log)

To download the demographic census data, run the `visualize.ipynb`.

#### Data 

Initially I saw this data at [usda/county-level-data-sets | data.world](https://data.world/usda/county-level-data-sets), originally from [USDA ERS - County-level Data Sets](http://www.ers.usda.gov/data-products/county-level-data-sets.aspx) in :

- [Education.xls](http://www.ers.usda.gov/webdocs/DataFiles/CountyLevel_Data_Sets_Download_Data__18026//Education.xls)
- [PovertyEstimates.xls](http://www.ers.usda.gov/webdocs/DataFiles/CountyLevel_Data_Sets_Download_Data__18026//PovertyEstimates.xls)
- [Unemployment.xls](http://www.ers.usda.gov/webdocs/DataFiles/CountyLevel_Data_Sets_Download_Data__18026//Unemployment.xls)
- [PopulationEstimates.xls](http://www.ers.usda.gov/webdocs/DataFiles/CountyLevel_Data_Sets_Download_Data__18026//PopulationEstimates.xls)

#### Useful links

- [Mapping the U.S. Census population estimates for incorporated places with CartoDB and geopandas](http://blog.danwin.com/census-places-cartodb-geopandas-mapping/)

- [GeoJSON and KML data for the United States](http://eric.clst.org/Stuff/USGeoJSON)

