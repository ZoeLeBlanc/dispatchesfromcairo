---
layout: post
cover: false
title: Finding Trends and Deforming Texts
date:   2016-06-22 10:18:00
tags: visualizations
subclass: 'post tag-visualizations'
categories: 'visualizations'
cover: 'assets/images/cover1.jpg'
navigation: True
logo: 'assets/images/logo.png'
---
In digital humanities, one of the foundational texts is Franco Moretti's *Distant Reading*, which was among the first to demonstrate the possibilities of text mining large corpuses of texts. 

While the concept of distant reading is increasingly being complicated and debated, Moretti's initial insight that transforming texts can provide new insights remains fundamental to digital humanities. Part of this debate over distant reading is the question of whether humanists should be able to write their own statistical models or if we can simply rely on processes developed for other disciplines. In the most recent *Debates in Digital Humanities*, Ben Schmidt argues that while most humanists will not be able to write algorithms or statistical models, they should understand how these applications transform their texts. This assertion sounds straightforward, but testing the parameters of a statistical model can be incredibly laborious, involving multiple excel sheets and datasets. 

Before jumping into these more complex models, a great way to start finding patterns and transforming texts is to use Voyant Tools, which is a free data visualization/text mining tool. I used the scatterplot function to help understand clustering within two boxes, and try to understand the contextual meanings of words like Congo or Bandung. 

Below you can see the scatterplots, and also try out some of the other features of Voyant Tools with my datasets. 

Record Group 84, Egypt US Embassy Records 1959-1961 Unclassified Box 9

<!--    Exported from Voyant Tools: http://voyant-tools.org/.
Please note that this is an early version and the API may change.
Feel free to change the height and width values below: -->
<iframe style='width: 100%; height: 800px' src='http://voyant-tools.org:80/?analysis=pca&limit=500&dimensions=2&clusters=5&comparisonType=raw&corpus=19c5cdf8c6b39b006736560a952526eb&view=ScatterPlot'></iframe>

Record Group 84, Egypt US Embassy Records 1959-1961 Unclassified Box 10 
<!--    Exported from Voyant Tools: http://voyant-tools.org/.
Please note that this is an early version and the API may change.
Feel free to change the height and width values below: -->
<iframe style='width: 100%; height: 800px' src='http://voyant-tools.org:80/?analysis=pca&limit=500&dimensions=2&clusters=5&comparisonType=raw&corpus=cdfff416e4d8ca9ff284cdbf32428081&view=ScatterPlot'></iframe>