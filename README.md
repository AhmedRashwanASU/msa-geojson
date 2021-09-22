# msa-geojson

## US Metro Area shapefiles into Dorling cartograms

## Source

http://opendata.dc.gov/

## Process

people to use them as alternatives to regular Census tract maps to improve the visualization of demographic data in urban environments.
1- Load the requierd libraries as below 
* library(httr)
* library(jsonlite)
* library( geojsonio )   # read shapefiles
* ibrary( sp )          # work with shapefiles
* library( sf )          # work with shapefiles - simple features format
* library( tmap )        # theme maps
* library( dplyr )       # data wrangling
* library( pander )      # nice tables 
* library( DT )
* library( knitr )
* library( stargazer )
### maps libraries 
* library( ggmap )
* library( leaflet )
* library( viridis )
* library(tidycensus)
* library( pals )
* library( cartogram )  # spatial maps w/ tract size bias reduction

## Datasets

> The data made available here has been modified for use from its original source, accuracy or content of any data contained in this application; makes any representation of any kind, including, but not limited to, warranty of the accuracy or fitness for a particular use; nor are any such warranties to be implied or inferred with respect to the information or data furnished herein. The data is subject to change as modifications and updates are complete. It is understood that the information contained in the web feed is being used at one's own risk.
