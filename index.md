---
title       : はじめてのslidify
subtitle    : マークダウンで楽々HTML5スライド作成
author      : "@kohske"
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

## 平均とは
 
- \(\frac{1}{n}\sum_{i}x_i\) ということです。
- 例えば1から10までの平均は5.5です。

### 乱数の生成

10000個の正規乱数を生成して平均値を求めます。


```r
set.seed(42)
x <- rnorm(10000)
mean(x)
```

```
## [1] -0.01131
```


---

## ヒストグラム

正規乱数をヒストグラムとカーブフィッティングにより可視化します。

<img src="assets/fig/fig-01.png" title="plot of chunk fig-01" alt="plot of chunk fig-01" style="display: block; margin: auto;" />






