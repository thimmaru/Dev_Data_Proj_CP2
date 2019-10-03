Dev Data Prod_CP2
========================================================
author: Thimmaraj Rudrappa
date: 3O Oct 2019
autosize: true

First Slide
========================================================

- Data source - mtcars
- Plotted using 'ploty'
- Slides - R studio presentation

Slide With Code
========================================================


```r
summary(mtcars)
```

Slide With Plot
========================================================
```r
library(plotly)
plot_ly(mtcars, x = ~wt, y = ~mpg, type = "scatter", color = ~factor(cyl), size = ~hp)
```
