---
title       : Find the car you would love!
subtitle    : Coursera Assignment
author      : Vijay Goel
job         :
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      #
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---
## Overview
Do you have difficulty finding a great car that you would love to have?
 
Well, we have built an application for you, specifically this purpose. It will help you by providing details of cars, that match your criteria.
 
It also lets you download the results, in case you want to print them, or do follow-ups offline.
 
Read along!

---
## How to access and use the app
 
You can view the application at
https://vijaygoel.shinyapps.io/DDR-Assgn-Find-Your-Car/
 
The left hand navigation provides space to input filters. You can select # of cylinder and class of car through checkboxes. MPG and year of model is provided in sliders.
 
Once you are done with changing filter ctireria, please click on 'Refine' button. This will change the results you see on right hand side.
 
Top bar will tell you how many results match your criteria, and second box will give you the complete list with specifications.
 
Once you have the right list to work with, you can also download the list by clicking on 'Download Results' button, towards bottom of left navigation bar.

---
## Basics of data at your disposal
 

```
## [1] "Total cars available in database -  234"
```
 
Criteria available to filter from, are:
 
- Number of cylinders,
- Class of car (e.g. compact, midsize),
- minimum city Miles Per Gallon (MPG),
- minimum highway MPG and
- year of model release
