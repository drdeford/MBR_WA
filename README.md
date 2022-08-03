# MBR_WA

This repository contains replication data and code for WA experiments in ``Multi-Balanced Redistricting,'' joint work with <a href="https://und.edu/directory/ryan.zerr"> Ryan Zerr <a/> (Professor of Mathematics at the Universit of North Dakota) and Elliot Kimsey (an undergradute student at WSU in our data analytics program!). 

The Data2020.zip file contains the processed shapefiles and dual graph used in the analysis. The Malaprop_Merge.ipynb notebook demonstrates the processing and compilation steps from various raw data sources but the initial datasets are not included here for size reasons. Source data was obtained from the <a href="https://www.census.gov/data/developers/data-sets.html">US Census API</a>, <a href="https://data2.nhgis.org/main#">NHGIS</a>, and the <a href="https://redistrictingdatahub.org/">Redistricting Data Hub</a>.  

The processed data has been loaded onto block groups from the 2020 census and includes total population, voting age population, citizenship estimates, American Community Survey 5 year average estimates, population projections through 2030 from HaystaqDNA, and population totals adjusted for individuals in state custody as described in the Rules Code of Washington 44.05.140. 

The Optimization_Notebooks directory contains jupter notebook and python script examples of the experiments described in Section 4 of the paper. Specifically, running them without adjustment will reproduce the experimental results described for optimizing for both the census population and each other comparison population column. 


