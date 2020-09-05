# GCPS Covid Data

This repo attempts to pull data from the [GCPS](http://publish.gwinnett.k12.ga.us/gcps/home/public/schools/content/return-to-learning-hub/covid19-info-by-school). 

In order to pull the data, I use the {tabulizer} package, but the pull is not always perfect, so it has required some more manual entry as well. 

All data cleaning happens in data_cleaning.Rmd. This is a somewhat brittle data cleaning process as it assumes that you clean the latest dataset on the day it was released and that the existing dataset you are adding to contains all the previous dates. It is not ideal and could be improved upon.  

The gcps_report.Rmd doc is a very simple report that needs to be developed more. 

