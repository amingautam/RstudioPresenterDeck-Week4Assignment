My ShinyApp Presentation
========================================================
author: Gautam Amin
date: 28-Feb-2016

What does the App Do?
========================================================
This application demonstrates the following:
-	Some form of input (widget: textbox,radio button,checkbox,..)
-	Some operation on the ui input in sever.R
-	Some reactive output displayed as a result of server calculations
-	Documentation so that a novice user could use your application.
-	The documentation should be at the Shiny website itself. Not an external link.

**Note:** Please use the HELP tab on the app to know how to use use the app and test
these features

Features:
========================================================
The UI has features to filter on columns & values of the data set so that you dont have to write code and deal with data like this:


```r
library(dplyr)
iris %>% select(Sepal.Length,Petal.Length) %>% filter(Sepal.Length == 5.1)
```

```
  Sepal.Length Petal.Length
1          5.1          1.4
2          5.1          1.4
3          5.1          1.5
4          5.1          1.5
5          5.1          1.7
6          5.1          1.5
7          5.1          1.9
8          5.1          1.6
9          5.1          3.0
```


More Features:
========================================================
<small>The App uses the IRIS dataset and allows you to dymanically select columns
to generate Summary and also Plots like this:</small>

```r
plot(iris, main="Iris Data")
```

![plot of chunk unnamed-chunk-2](ShinyAppPresentation-figure/unnamed-chunk-2-1.png)


How Do I access the Shiny App & its code & code for this Presentation?
========================================================
- The Shiny app: https://amingautam.shinyapps.io/ShinyProjectWeek4Assignment/
- Git repo for ShinyApp: https://github.com/amingautam/ShinyApp-AssigmentWeek4

- Git Repo for this presentation: https://github.com/amingautam/RstudioPresenterDeck-Week4Assignment

