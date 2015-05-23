---
title       : MPG Shiny App
subtitle    : 
author      : Sergei P.
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## The problem

- You have a specific task to analyze relationships between one particular variable and a set of others. For example, you are interested in miles per gallon output of a car and what might affect it. 
- You have to present your conclusions and the way you came up with them to general public.
- And then you see this:


```r
head(mtcars)
```

```
##                    mpg cyl disp  hp drat    wt  qsec vs am gear carb
## Mazda RX4         21.0   6  160 110 3.90 2.620 16.46  0  1    4    4
## Mazda RX4 Wag     21.0   6  160 110 3.90 2.875 17.02  0  1    4    4
## Datsun 710        22.8   4  108  93 3.85 2.320 18.61  1  1    4    1
## Hornet 4 Drive    21.4   6  258 110 3.08 3.215 19.44  1  0    3    1
## Hornet Sportabout 18.7   8  360 175 3.15 3.440 17.02  0  0    3    2
## Valiant           18.1   6  225 105 2.76 3.460 20.22  1  0    3    1
```


--- .class #id 

## What would you do?

- You know that the best way to do this is to make lots of plots and linear models. But how would you explain to general public the way came up with this pretty plot?

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 

---

## You need a shiny app!
<img class=center src="http://40.media.tumblr.com/c0a592a6e36347554351404e50de519e/tumblr_no8mxbNVz61shtwfqo1_1280.jpg" height=323 />
<p class=left><small><a href="http://thinkingaboutbears.tumblr.com/image/118777229359">thinkingaboutbears.tumblr.com</a></small></p>

- The app must allow to plot different variables against mpg variable.
- It also should allow to fit linear models and show their summaries as well as plot them.

---

## Introducing MPG-app!

![image](pics/scr-1.png)

- Try it here [https://pased.shinyapps.io/mpg-app/](https://pased.shinyapps.io/mpg-app/)

---

## Source and documentation

- You can checkout the code here: [https://github.com/pased/mpg-app](https://github.com/pased/mpg-app)
- The documentation is available in the 'Documentation' tab of the app.
