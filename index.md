---
title       : Test 2 First Deck
subtitle    : subtitle for test
author      : Sebastien Dupuis
job         : Director
framework   : shower        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## Slide 2


```r
sum(1:10)
```

```
## [1] 55
```

```r
10*11/2
```

```
## [1] 55
```

---

## Slide 3


```r
fit <- rnorm(10,1)
summary(fit)
```


---

## Slide 4


```r
fit <- rnorm(10,1)
summary(fit)
```

```
##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
## -0.2748  1.0550  1.2060  1.0830  1.4910  2.0520
```

