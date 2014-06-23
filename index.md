---
title       : Canada's Gross Domestic Product (GDP) estimator
subtitle    : An homework assignment for the Developing Data Products course
author      : Etienne Laurin
job         : Student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}

--- .class #id 

## Overview

This is an overview of the application "[Canada's Gross Domestic Product (GDP)](https://etiennelaurin.shinyapps.io/CanadaGDP/)".

To run it, follow the link above and select a year and a territory.

In the right panel, you will see the estimate in million chained (2007) dollars.

--- .class #id 

## Data and Methodology

Origin of the data:
* Statistics Canada, Canada's official federal statistics agency
* Based on the GDP data from 1981 to 2012
* Public data
* CANSIM table 384-0038

Predictors use:
* Province or territory
* Year
 
Method:
* Generalized linear model (GLM)

--- .class #id 

## Purpose

* GDP growth is an indicator of economic prosperity



For example, in the year 2016, ceteris paribus, Quebec's GDP should be approximately 265355 million chained (2007) dollars.

--- .class #id 

## Accuracy



Root mean squared error:
5.0166 &times; 10<sup>4</sup>

R squared:
0.9561
