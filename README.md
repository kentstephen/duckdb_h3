# Notebooks using DuckDB with the H3 Extension and Overture Maps Data

![pictures/kepler.gl (1).png](https://github.com/kentstephen/duckdb_h3/blob/main/pictures/kepler.gl%20(1).png)

#### *The latest DuckDB 1.1.0 now reads geoparquet natively. So that means all of these queries with `ST_GeomFromWKB` will break*
 * I am going to update them soon but for now just take out `ST_GeomFromWKB()` *Now all but [montpelier_water_buildings.ipynb](montpelier_water_buildings.ipynb) is updated.*

### In [tlc_overture_lonboard.ipynb](https://github.com/kentstephen/duckdb_h3/blob/main/tlc_overture_lonboard.ipynb) and [tlc_overture_kepler.ipynb](https://github.com/kentstephen/duckdb_h3/blob/main/tlc_overture_kepler.ipynb) I demonstrate how you can generate H3 from taxi data and merge it with Overture Buildings with those respective mapping libraries.

### In [montpelier_water_buildings.ipynb](montpelier_water_buildings.ipynb), I visualize the volume of buildings near water.

### In [egypt_building_density.ipynb](egypt_building_density.ipynb) I look at building density.
