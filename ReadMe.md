# TravellingSalesmanProblem-in-PolishVoivodeships

This project uses the python libraries 'geopandas' and 'python-tsp' to solve the Travelling Salesman Problem in Polish Voivodeships.

The script uses the shapefiles of Polish Voivodeships and district cities, and plots the chosen voivodeships on the map along with all district cities.
The script then selects all district cities within the chosen voivodeships and applies the TSP algorithm to find the shortest path visiting all the selected cities.
The script also provides a visual representation of the shortest path on the map.
This project can be used as a starting point for solving the TSP problem in any region, by replacing global variable containing chosen regions.


Data comes from: https://www.diva-gis.org/datadown

![path](https://user-images.githubusercontent.com/101405852/212161187-05c4cdc8-6dc4-4fc5-a2af-3b82e0013ca1.png)
