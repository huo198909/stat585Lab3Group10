---
title: "README"
author: "Lab3_Group10"
date: "3/23/2019"
output:
  html_document:
    keep_md: True
---

Link to our repo
`https://github.com/stharms/stat585Lab3Group10`

## Description
This package provides three different methods to format spatial polygon geometry for easy plotting in R

## Installation
The package can be installed with `devtools::install_github('stharms/stat585Lab3Group10')`

## Contents 
We have 3 functions, all of which take arguments 'file' and 'tolerance' and return a dataframe:

`team_12` by Steve Harms

`team1` by Yonghui Huo

`team_10` by Dapeng Hu

## Notes
The team_12 and team_10 functions contain an additional parameter, `fileread = T`, that can be changed to `FALSE` in order to apply the function to an R object that is not a file. We did this because .shp files are not allowed as sample data, but if we read the .shp file in as an R object first we can then keep it as our data. We use this data for examples for each function.
