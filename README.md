# Phoenix Light Rail Study
Project Status: `completed`

This was my first ever GIS final project back when I was taking my GIS I class. The goal of the project was to apply the spatial analysis techniques from class on a freely available dataset using QGIS. The goal was to ultimately show an interesting and non-obvious phenomenon. 

For my project, I decided to place a price tag on the value of Phoenix Light Rail as it relates to accessibility. Specifically, I wanted to divide the number of people served by the light rail line by the line's construction cost to get a sense of the cost per newly accessible resident. Then, using that cost figure, I could compare it to the estimated cost and accessibility of future light rail extension projects.

In the end, I found that two of the four extension projects will have a high cost of accessibility, meaning that the light rail project will serve less people per dollar spent on the project. Meanwhile, the other two extension projects would serve either the same or more people per dollar spent compared to the original light rail line.

## Geospatial Analysis Tools and Functions Used
* Basic geospatial functions (Unions, Dissolves, Centroids...) in QGIS3 
* Spatial Data Joins in QGIS3 
* Isochrone creation with Openroute Service API

## Data Sources
* U.S. 2010 Census & American Community Survey (ACS) Data
* Phoenix Valley Metro Rail Open Data Portal
