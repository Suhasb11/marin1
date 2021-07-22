# marin1
This app is developed for tracking the ship

1. convert the csv file to feather format to increase the speed
2. files used 
app.R - main file containing ui and server
mapserver - shiny module for server components
uimodule - all ui components of shimy module

library(gaugeR)
library(shiny)
#library(shinyDashboardThemes)
library(shinyjs)
library(shinythemes)
library(shiny.semantic)
library(semantic.dashboard)

library(dplyr)
library(leaflet)
library(geosphere)
library(plotly)
library(testthat)
library(feather)
