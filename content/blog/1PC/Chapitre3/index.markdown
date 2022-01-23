---
title: "Chapitre 3 : le chp3"
subtitle: "subtitle"
excerpt: "excerpt field"
date: '2021-10-28'
draft: false
math: true
weight: 3
editor_options: 
  markdown: 
    wrap: 72
---

## Le premier titre du chap 3

Ainsi, pour caractériser un système chimique il nou faudra simplement
compter les atomes. Malheureusement ceux-ci sont en nombre gigantesque.
Dans une goutte d'eau il y a `\(16 \times 10^{20}\)` molécules H$_2$O. Il
nous faut donc trouver un moyen de compter les molécule et atomes par
paquet et non un par un. Ces paquets sont appelés moles.

Une mole d'entités contient exactement `\(6,022 140 76 \times 10^{23}\)`
entités (atomes ou molécules). Nous utiliserons la valeur arrondie à
`$6 \times 10^{23}$` entités.

> Le nombre d'entités, atomes, molécules, particules, ions etc... dans une mole de matière est la constante d'Avogadro. 
> Elle est notée
> `$$N_A = 6,02 \times 10^{23} \text{ entités / mol}$$`

## le second 

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

