# Notebooks using DuckDB with the H3 Extension and Overture Maps Data

## *The latest DuckDB 1.1.0 now reads geoparquet natively. So that means all of these queries with `ST_GeomFromWKB` will break*
I am going to update them soon but for now just take out `ST_GeomFromWKB()`

### In [montpelier_water_buildings.ipynb](montpelier_water_buildings.ipynb), I visualize the volume of buildings near water.

### In [egypt_building_density.ipynb](egypt_building_density.ipynb) I look at building density.

### In [road_complexity.ipynb](road_complexity.ipynb) I look at road complexity by aggregating intersections.
