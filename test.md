DDP W3 COVID19 CDC Cases
========================================================
author: Patrick Brooks
date: 04/15/2020
autosize: true

Purpose
========================================================

The United States Centers for Disease Control (CDC) provides a simple CSV file 
of reported [COVID-19](https://www.cdc.gov/coronavirus/2019-ncov/cases-updates/cases-in-us.html)  cases.  The data table contains the state, recorded cases, the state CDC page.  This exercise will use Leaflet to produce an interactive map of this data.  
The code used in this exercise is based in part on a [Plotly Choropleth example](https://plotly.com/r/choropleth-maps/).  

Methodology
=======================================================
The CDC data contains several US territories not covered by the Plotly map.  The CDC data was
manually cleaned for expediency.  Also a two character code was added to the data file for
Plotly to recognise the state data. 

* A simple "Blues" pallet was used to color code the states based upon the reported cases.  
* A hover varialbe was added and the user can mouse over a state and see cases and the State's CDC site.  
* A legend was added for a macro understanding of the cases reported.  



Slide With Code
========================================================
title: false

<iframe src="map.html" style="position:absolute;height:100%;width:100%"></iframe>


 Summary & code listing
========================================================
This project demonstrates that creating simple interactive spacial maps can be accomplished
with a a little creative effor.  Below is the code that generated the graphic.

