1. I have used **Dataframe_cleanup_NPTEL.ipynb** file to clean, organise and rectify the dataset **apy.csv**.
2. **apy_filtered.csv** is the filtered dataset with null values removed, name of the crops rectified, I have also removed some crop like Apple, Pear etc. from the dataset because they do not contain any detailed information.
3. You can find both the datasets (filtered and original) in **Datasets** folder.

# Choropleth maps
District wise crop production plots like the following has been plotted for top 5 produced crops using [**geopandas**](https://geopandas.org/en/stable/about.html) and [**matplotlib**](https://matplotlib.org/)
![Coconut Production Map](/../assets/Assets/coconut_production_avg_reduced.png)

# Year-wise crop production plot
Total crop production is plotted with years like following with **matplotlib** and smoothening is done by **scipy.interpolate**.
![Yearly rice production](/../assets/Assets/rice_yrp.png)

Note: 

Shapefile of the Map used in this project can be found [here](https://geodata.lib.utexas.edu/catalog/stanford-sh819zz8121)
