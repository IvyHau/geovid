---
title: 'Data Preparation & Analysis'
date: 2019-02-11T19:27:37+10:00
weight: 8
---

**Data Preparation**

* Data Collection

Data of the cases of coronavirus in Hong Kong, the quarantine building list, means of transport, population, as well as testing, are obtained from data.gov.hk, the Hong Kong government’s open data source.

* Data Cleaning and Wrangling

The data cases has to be clean to extract only data from January to September. Duplicates will also need to be checked to prevent skewed data analysis. Data Standardization will then ensure the same data types to ensure a fairer comparison and analysis.

* Data Transformation

As the study analyses the intensity and relationships, the data has to be transformed to the relevant formats before more statistical analysis can be done. Such transformations are converting SpatialPointDataFrame to Point Pattern Processes. Shapefile for the geographic area will need to be converted to owin in order to analysis the points in the study area.

**Data Analysis**

* Exploratory Data Analysis

Exploratory Data Analysis will first be used to describe the data and general observations that could be observed

* Global/Local Moran's I

Global Moran I will be used to analyse the autocorrelation of objects with the global area. 

Local Moran's I will be used to analysed the autocorrelation on the local level.

* Getis and Ord's G-Statistics

Getis and Ord's G-Statistics will be used to analyse the statistically significant hot and cold spots.