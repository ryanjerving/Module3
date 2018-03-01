---
title: "Module 3 HTML Document"
author: "Ryan Jerving"
date: "February 28, 2018"
output: 
  html_document:
    fig_width: 5
    highlight: tango
    theme: cosmo
    toc: yes
    toc_float: true
    code_folding: hide
    keep_md: true
---



# Module:  HTML Document

## R Markdown {#nextsteps .emphasized}

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

## Including Plots

You can also embed plots, for example:

### Cars Plot


```r
plot(cars)
```

![](Module3_files/figure-html/cars-1.png)<!-- -->

### Pressure Plot


```r
plot(pressure)
```

![](Module3_files/figure-html/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

## A short list

* apples
* oranges
* bananas

## An equation

$$E = mc^2$$
