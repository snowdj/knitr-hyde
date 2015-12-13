---
layout:  post
title: "Sample Post"
comments:  true
published:  true
author: "Homer White"
date: 2015-12-12 20:00:00
categories: [R]
output:
  html_document:
    mathjax:  default
    fig_caption:  true
---




This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:



{% highlight r %}
summary(cars)
{% endhighlight %}



{% highlight text %}
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
{% endhighlight %}

You can also embed plots, for example: 


![plot of chunk unnamed-chunk-3](/knitr-hyde/figure/source/2015-12-12-sample-post/unnamed-chunk-3-1.png) 

<p class = "figcaption">Here is a plot for you.</p>

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

You can do math, too:  inline math is like this:  $$ \pi/2 \approx 1.57 $$ and displayed math as well:

$$ \sum_{i=1}^{n} i = \frac{n(n+1)}{2}.$$

How lovely.
