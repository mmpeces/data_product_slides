---
title       : Average miles per gallon (MPG) shiny app 
subtitle    : using mtcars data
author      : mmpeces
job         : student
framework   : html5slides        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

<h3> Estimating MPG for different cylinder engines
<h4> using mtcars data


--- 
Overview

A simple shiny app was built for the Developing data products project.  The application used the mtcars data to get the average miles per gallon based on the number of cylinders.  The app uses a text widget which the number of cylinders is entered by the user.  Although, per the project instructions the application was kept simple, more predictors can be added to increase the usefulness of the app.  A description of the mtcars data can be found at:
        http://stat.ethz.ch/R-manual/R-devel/library/datasets/html/mtcars.html.
        
The shinyapp is located at: https://mmpeces.shinyapps.io/mpg_cylinders/

---
Why my shiny app is useful (or the pitch).

Aid in predicting or estimating the number of miles per gallon (mpg) a vehicle will get is useful due to rising fuel cost and specialization of knowledge. 

-With the overall trend of an increase in gas prices for the foreseeable future it is important to consider fuel economy when purchasing a new or used car.  New cars post the fuel efficiency but with used cars buyers need to determine fuel efficiency on their own.  One strong indicator of efficiency is the number of cylinders. 

-Although in general older members of society have a good grasps of the inverse relationship between miles per gallon and number of cylinders, younger citizens make lack the general knowledge due to the substantial arcane learning necessary for our ever more technical and diverse work force.  

---
The data


```
##        MPG
## 4 26.66364
## 6 19.74286
## 8 15.10000
```

Results for each indivdual cyclinder are above.  The difference is more apparent when we see the plot.

---

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 






