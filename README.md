## COVID-19 confirmed case visualisation shiny app

This app visualise the number of confirmed cases and total cases for selected countries, 
reading the data from https://covid.ourworldindata.org/data/owid-covid-data.csv. 
This app is a part of lecture for DATA3888 (2021) in the University of Sydney.

Run the app locally in Rstudio on laptop by

```
library(tidyverse)
library(ggthemes)
library(plotly)
shiny::runGitHub(
  repo = "DATA3888_COVID_shiny", 
  username = "yingxinlin", 
  ref = "main")
```
