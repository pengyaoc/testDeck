---
title       : BMI Calucater
subtitle    : Awesome way to measure your health
author      : Pengyao Chen
job         : Body Builder
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz]  # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Outline

1. Can you tell if this guy has normal weight?

2. Why is BMI measurement useful?

3. BMI Categories

--- &radio

## Question

Peter weighs 200 lb. Can you tell if this guy is over weight?

1. Over weight
2. Noraml weight
3. Under weight
4. _hard to tell_

*** .hint
Think football player.

*** .explanation
Since we don't know how tall the guy is, we have no idea if he is over weight or not.

---

## Why is BMI measurement useful?

This measurement combines the inforamtion of height and weight to give a much better estimate on your weight condition.
If you are taller than most people, it makes sense for you to be heavier as well. 
Not so much when you are shorter than average.

A man with 5 feet 9 and 132 pound has a bmi of 

```r
703 * 132 / (5 * 12 + 9) ^ 2
```

```
## [1] 19.49
```

---

## BMI Categories

1. Underweight less than 18.5

2. Normal weight equals 18.5–24.9

3. Overweight equals 25–29.9

4. Obesity greater than 30
