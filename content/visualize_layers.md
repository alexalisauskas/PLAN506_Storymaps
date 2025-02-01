---
layout: default
title: Visualize Your Layer Data
nav_order: 6
parent: Create a Web Map
---

## Visualize Your Layer Data

### Sample Data

You can download the data below and add each file as a layer to your ArcGIS Online webmap to play around with features.

**Vancouver_Commuter_2016.geojson** is a polygon layer with commuter data joined to local area boundaries.

**bikeways.geojson** is a line layer showing Vancouver bike paths

**heritage-sites.geojson** is a point layer showing Vancouver heritage sites.

[Download Data](./StorymapsWorkshopData.zip){: .btn .btn-blue }


### Styles

#### Counts and Amounts
Read more about [Data Classification Methods](https://pro.arcgis.com/en/pro-app/latest/help/mapping/layer-properties/data-classification-methods.htm) and how you might want to use them.

### Filtering for certain elements
Use the filter feature to create a condition and determine what shows up on your map. This feature is useful if you have data that varies in type/category or date. you can also filter to only include features in a certain neighbourhood.

If you want to create a Swipe on your Storymap, the Filter function can be very useful to single out data and create the individual maps that make up the Swipe. Once you've filtered the data you want to show, make sure to "Save as" your map. In the example below I have filtered heritage sites in the local area of Kitsilano.

<img src="images/VancouverData.png" alt="fig1" style="width:400px;"/>

To try{: .label .label-green } 
- On the heritage_sites layer, try filtering to include only archeological sites
- On the Bikeways layer, try filtering to include only bikeways created in the 1990s

### Aggregation

You can enable aggregation on your map. 

**Binning** aggregates data to predefined cells, representing point, line, or polygon data as a gridded polygon layer. The bins show point, line, or polygon density in geographic space instead of screen space.

**Clustering** aggregate points into clusters and display them as one symbol. Clusters use proportionally sized symbols and change dynamically with the map scale. Clustering only works for point features.

<img src="images/Clustering.png" alt="fig1" style="width:400px;"/>

Spatial aggregation is one method for visualizing high-density data. Read more about [Best practices for visualizing high-density data](https://doc.arcgis.com/en/arcgis-online/reference/best-practices-high-density-data.htm)

### Pop Ups

### Fields

### Labels

### Add Sketch

#### More Resources
- For more in-depth instructions and examples, visit our workshop [Visualizing Data in ArcGIS ONline}(https://ubc-library-rc.github.io/intro-AGOL/)
