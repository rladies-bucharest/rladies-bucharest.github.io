---
autoThumbnailImage: false
categories:
- blog
- tranquilpeak
coverImage: //d1u9biwaxjngwg.cloudfront.net/welcome-to-tranquilpeak/city.jpg
date: "2020-01-29"
keywords:
- blogdown
metaAlignment: center
tags:
- hexo theme
- responsive
- hugo
- blogdown

thumbnailImage: //d1u9biwaxjngwg.cloudfront.net/welcome-to-tranquilpeak/city-750.jpg
thumbnailImagePosition: top
title: Rstudio::conf 2020 & tranquilpeak theme
---
In urma intalniri din Ianuarie 2020, mi-am dorit sa ne organizam informatia comunitatii intr-un site construit de noi cu R. Prin urmare, am inceput sa studiez subiectul si am descoperit thema Tranquilpeak din framework-ul Hugo.
<!--more-->

![Tranquilpeak](/img/showcase.png)
Tranquilpeak este o tema Hugo pentru toate categoriile de website - desktop, mobile si tablete, ce includ blog. Avand multe functionalitati si servicii integrate, pe care vom incerca sa le includem si astfel sa imbunatatim experienta cititorilor nostri.
<!-- toc -->
```{r setup, include=FALSE}
knitr::opts_chunk$set(collapse = TRUE)
```

# Fisiere R Markdown

Aceste este un document R Markdown. Markdown este o sintaxa simpla de formatare a documentelor de tip HTML, PDF si MS Word. Pentru mai multe detalii despre R Markdown vizitati: <http://rmarkdown.rstudio.com>.

Este foarte fain, deoarece poti include bucati de cod R, precum cel de mai jos:

```{r cars}
summary(cars)
fit <- lm(dist ~ speed, data = cars)
fit
```

# Include Grafice

Se pot include grafice. Vedeti figura de mai jos:

```{r pie, fig.cap='A fancy pie chart.', tidy=FALSE}
par(mar = c(0, 1, 0, 1))
pie(
  c(280, 60, 20),
  c('Sky', 'Sunny side of pyramid', 'Shady side of pyramid'),
  col = c('#0292D8', '#F7EA39', '#C4B632'),
  init.angle = -50, border = NA
)
```


