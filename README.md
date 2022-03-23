## COVID-19 confirmed case visualisation shiny app

This app visualises the number of confirmed cases and the total cases for selected countries, 
reading the data from https://covid.ourworldindata.org/data/owid-covid-data.csv. 
This app is a part of lecture for DATA3888 (2021, 2022) in the University of Sydney.

Run the app locally in Rstudio on laptop by

```
library(tidyverse)
library(ggthemes)
library(plotly)
library(shiny)
shiny::runGitHub(
  repo = "DATA3888_COVID_shiny", 
  username = "yingxinlin", 
  ref = "main")
```
