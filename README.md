#SF Crime Explorer

## Introduction

This application creates an interactive visualization tool to explore San Fransisco crime data from 2015. 
The application is composed of two scripts: `ui.r`, which initializes the user interface and `server.r`, which updates 
data queries. Data were acquired from https://www.kaggle.com/c/sf-crime and cleaned to represent crimes in 2015 only. 

## Recommended modules

Before running the application from an RStudio window, it is recommended to install the following packages as follows:

`install.packages(c("shiny","ggmap","leaflet","readr","dplyr","geosphere","stringr","shinydashboard"))`

## Usage

Run the application from the RStudio command line as follows:

`shiny::runGitHub('sfhansen/SF_Crime_Explorer')`

Once application is running, click the map in two location to display the crimes in their overlapping region. Apply filters as desired. 

## Credits

Authors: Samuel Hansen and Shirbi Ish-Shalom
