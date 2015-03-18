---
layout: post
title: "How to calculate ANOVA in Excel 2013"
modified:
categories: blog
excerpt: A demonstration of applying ANOVA in Excel 2013
tags: [Excel,ANOVA,Statistics]
image:
  feature:
date: 2015-03-11T15:39:55-04:00
comments: true
share: true
---

ANOVA is a hypothesis testing technique. It determines equality between two or more population mean .It determines that difference between samples are by chance or due to systematic treatment effect. We can calculate ANOVA in Excel. We can Understand how to calculate by following example.

Example: A Dietician testing weight loss techniques. He have three options

* Diet
* Exercise and
* Diet and Exercise both 

He takes 27 peoples and divide into three groups.9 undergo in diet program 9 in Exercise and another 9 in diet and exercise both. Written below is the weight loss per kg achieved using different methods.


<figure>
	<a><img src="/images/2014-08-08-How-to-calculate-ANOVA-in-Excel-2013-1.png" alt="image"></a>
	<figcaption>Weights of the subjects</figcaption>
</figure>


First we set up a hypothesis


H0: μ1 = μ2 = μ3


H1: at least one of the means is different.


To perform single factor ANOVA, execute following steps.


1.Click on Data Menu, on top right-click on Data Analysis. If you don’t find Data Analysis Option [click here](https://statistics4beginners.wordpress.com/2015/02/18/how-to-enable-data-analysis-option-in-excel-2013/) to see how to enable Data Analysis Option.

<figure>
	<a><img src="/images/2014-08-08-How-to-calculate-ANOVA-in-Excel-2013-2.png" alt="image"></a>
	<figcaption>Enable Data Analysis Option</figcaption>
</figure>

2.Select ANOVA: single factor and click OK
<figure>
	<a><img src="/images/2014-08-08-How-to-calculate-ANOVA-in-Excel-2013-3.png" alt="image"></a>
</figure>


3.Click in the input range box and select range A2 to C10

4.Click in the output range and select E1 Cell


<figure>
	<a><img src="/images/2014-08-08-How-to-calculate-ANOVA-in-Excel-2013-5.png" alt="image"></a>
</figure>

5.Click ok 

Result


<figure>
	<a><img src="/images/2014-08-08-How-to-calculate-ANOVA-in-Excel-2013-6.png" alt="image"></a>
</figure>

Conclusion: if F > F crit, we reject the null hypothesis. This is the case, 23.65517 > 3.402826. Therefore, we reject the null hypothesis. The means of the three populations are not all equal. At least one of the means is different. However, the ANOVA does not tell you where the difference lies. You need a t-Test to test each pair of mean