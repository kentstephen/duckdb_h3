# Notebooks using DuckDB with the H3 Extension and Overture Maps Data

![kepler gl (1)](https://github.com/user-attachments/assets/5dcd6e47-ee66-48b4-a5a9-2f78e8a28eba)

## *The latest DuckDB 1.1.0 now reads geoparquet natively. So that means all of these queries with `ST_GeomFromWKB` will break*
I am going to update them soon but for now just take out `ST_GeomFromWKB()` Now all but [montpelier_water_buildings.ipynb](montpelier_water_buildings.ipynb) is updated.

### In [montpelier_water_buildings.ipynb](montpelier_water_buildings.ipynb), I visualize the volume of buildings near water.

### In [egypt_building_density.ipynb](egypt_building_density.ipynb) I look at building density.
