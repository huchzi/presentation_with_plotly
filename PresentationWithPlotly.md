---
title: "RMarkdown presentation With Plotly"
date: "26 May 2017"
output: ioslides_presentation
---




## First Slide

My plot is based on the cars dataset. This dataset consists of two variables: speed in mph and stopping distance in feet.

Show the dataset
========================================================


```
  speed dist
1     4    2
2     4   10
3     7    4
4     7   22
5     8   16
6     9   10
```

Plot with ggplotly
========================================================



```
processing file: PresentationWithPlotly.Rpres
Loading required package: ggplot2

Attaching package: 'plotly'

The following object is masked from 'package:ggplot2':

    last_plot

The following object is masked from 'package:stats':

    filter

The following object is masked from 'package:graphics':

    layout

Quitting from lines 31-43 (PresentationWithPlotly.Rpres) 
Fehler in loadNamespace(name) : there is no package called 'webshot'
Ruft auf: knit ... tryCatch -> tryCatchList -> tryCatchOne -> <Anonymous>
Zusätzlich: Warnmeldung:
We recommend that you use the dev version of ggplot2 with `ggplotly()`
Install it with: `devtools::install_github('hadley/ggplot2')` 
Ausführung angehalten
```
