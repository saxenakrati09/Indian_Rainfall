# Indian_Rainfall


EDA on Indian Rainfall dataset
------


gmaps module has been used in the notebook.
But maps are not visible in the Jupyter Notebook.

Below are the screenshots of Maps output from the code

`fig = gmaps.figure()`

`gini_layer = gmaps.geojson_layer(india_geojson, fill_color='blue')`

`fig.add_layer(gini_layer)`

`fig`

#### Output
![Preview](https://github.com/saxenakrati09/Indian_Rainfall/blob/master/map%20(1).png)





`fig = gmaps.figure()`

`gini_layer = gmaps.geojson_layer(india_geojson, fill_color='white')`

`fig.add_layer(gini_layer)`

`heatmap_layer = gmaps.heatmap_layer(
                annual_rainfall_states[['Latitude', 'Longitude']], weights = annual_rainfall_states['ANNUAL'],
                max_intensity = 100000, point_radius = 30.0)`

`fig.add_layer(heatmap_layer)`

`fig`

#### Output
![Preview](https://github.com/saxenakrati09/Indian_Rainfall/blob/master/map%20(2).png)

## Kaggle Kernel Link
https://www.kaggle.com/kratisaxena/indian-rainfall-analysis
