---
title: "DataScienceProfile"
author: "Michael Tieu"
date: "9/13/2018"
output: 
  html_document:
    keep_md: true
---
#testrepo


```r
Categories <- c("Computer Programming", "Math", "Statistics", "Machine Learning", "Domain Expertise", "Communication and Presentation Skills", "Data Visualization")
Ranking <- c(2,4,3,1,1,3,2)
dataframe <- data.frame(Categories,Ranking)
#View(dataframe)
par(las=2)
barplot(Ranking, main="Data Science Profile", names.arg=Categories, cex.names=0.5)
```

![](DataScienceProfile_files/figure-html/unnamed-chunk-1-1.png)<!-- -->
