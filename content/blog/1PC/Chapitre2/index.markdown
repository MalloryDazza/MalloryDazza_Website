---
title: "Chapitre 2 : Le 2"
subtitle: "le sous titre"
excerpt: "excerpt filed"
date: '2021-09-30'
draft: false
math: true
weight: 2
editor_options: 
  markdown: 
    wrap: 72
---

## Le premier titre du chap 2 

Other times, I have not used X (yet!). This happened to me recently when
I was asked: 

> *"Why aren't people using reveal.js for slides with R
Markdown? What are the problems with reveal.js, and how can we fix
them?"*. 

What is reveal.js? Here is a demo deck:

<iframe src="https://revealjs.com/demo/" width="672" height="400px" data-external="1"></iframe>

## Air quality


```r
with(airquality, boxplot(Temp ~ Month))
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-2-1.png" width="672" />



```r
with(airquality, plot(Ozone ~ Temp))
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-3-1.png" width="672" />


```r
mlev <- levels(with(airquality, as.factor(Month)))
with(airquality, plot(Ozone ~ Temp, 
                      pch = as.numeric(mlev), 
                      col = mlev))
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-4-1.png" width="672" />

