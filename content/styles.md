---
layout: default
title: Style Tools
nav_order: 7
parent: Create a Web Map
---

# Layer Styles
The Style tools available to you will depend on the features in your layer, and the fields you select to map. The default style is Location (single symbol), which shows the geographic boundaries, lines, or points of your data.
 
There are many different map types you can create easily on ArcGIS online, so play around with adding fields and seeing the options. We will go through a few map types and how to create them.

Read more about [ArcGIS Online's Smart Mapping Styles](https://doc.arcgis.com/en/arcgis-online/create-maps/apply-styles-mv.htm).

## Counts and Amounts (color) aka Choropleth


Read more about [Data Classification Methods](https://pro.arcgis.com/en/pro-app/latest/help/mapping/layer-properties/data-classification-methods.htm) and how you might want to use them.


## Counts and Amounts (size) aka Proportional Symbol

## Dot Density Map

## Heat Map
A heat map shows areas of high activity with stronger colors that appear to glow hotter. It requires point features.

<img src="images/Filter_Heritage.png" alt="fig1" style="width:400px;"/>

## Types (Unique Symbol)
Types (Unique Symbol) shows different categories of features — such as type of tree, road class, or province name — with different colors. Some categories will not have an inherent order. For categories that do, such as educational attainment and income, consider using a sequential color ramp to visualize ranked categories.

The map below shows bike paths by type. Note how the basemap has been changed to ensure these elements stand out.

<img src="images/TypeUnique.png" alt="fig1" style="width:400px;"/>

## Compare A to B
If you want to compare data from two fields, you can use Compare A to B. The first attribute is compared to the second attribute, and represented as a simple ratio, or as "A as a percent of B." Examples: Revenue / Cost of Sale, or Corn Acres / Total Acres, or Corn Acres / (Corn + Wheat Acres).

The map below represents Walker commuters as a percent of total walkers.

<img src="images/ConpareMap.png" alt="fig1" style="width:400px;"/>

There are other comparison maps you can create as well. Play around with adding multiple data fields and seeing what comes up. Click on the i to learn more about each and how to use it.

#### More Resources
For more in-depth instructions and examples, visit our workshop [Visualizing Data in ArcGIS ONline](https://ubc-library-rc.github.io/intro-AGOL/)
