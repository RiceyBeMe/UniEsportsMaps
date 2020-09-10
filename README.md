# UniEsportsMaps
This repositor contains a bunch of files designed to create maps for UK University Esports.

List of universities from [NSE Points Table](https://nse.gg/), however small modifications could make this work for any list of Universities.

The Jupyter Notebooks in this repositor walk through the process of generating all the files.

## Folders
**csv** - Contains .csv files with Uni stats and coordinates  
**regions** - Contains GeoJSON formatted .json files with premade university regions  
**uk_outlines** - Contains GeoJSON formatted .json files of the uk outline
## Modules
### Core
[NumPy](https://numpy.org/)  
[Pandas](https://pandas.pydata.org/)  
[matplotlib](https://matplotlib.org/)  
[shapely](https://pypi.org/project/Shapely/)
### Optional
[geopy](https://pypi.org/project/geopy/) - Finding the location of Universities  
[geovornoi](https://pypi.org/project/geovoronoi/) - Creating voronoi regions
## Additional downloads
[ukoutline GeoJSON](https://github.com/martinjc/UK-GeoJSON)