---
layout: post
cover: false
title: Rhodesia in Cairo
date:   2016-06-22 10:18:00
tags: visualizations research
subclass: 'post tag-visualizations'
categories: 'visualizations' 
cover: 'assets/images/cover1.jpg'
navigation: True
logo: 'assets/images/logo.png'
---

In my larger dissertation, "Constructing Anti-Colonial Cairo", I explore how Cairo became a hub for anti-colonial movements across the globe. In particular, Cairo was an important site for African liberation movements. Nasser in 1958 established funds for these movements to set up offices in Cairo and produce materials in support of their movements. Furthermore, many anti-colonial leaders traveled to Cairo to meet with diplomats of the Eastern bloc since travel to Moscow or Beijing was usually prohibited or difficult. 

While historians have explored aspects of this history, reconstructing these anti-colonial networks in Cairo remains difficult. Part of the problem is that the Egyptian state archives of this time period are largely closed to foreign researchers, and researching in Egypt is increasingly dangerous. Furthermore, many of these anti-colonial leaders from other countries did not write much about their time in Cairo. One option historians have explored is traveling to multiple national archives of other countries. This approach does require a great deal of funding and there are not many post-colonial countries with state archives. However, national archives in the 'West' are usually fairly accessible and comprehensive. This solution is one I've adopted to help triangulate my Egyptian press sources.

A further benefit of this approach is that embassies in Cairo generally noted when members of these anti-colonial movements traveled to the city. However, finding that one slip of paper can be difficult in a mountain of archival sources.

One solution is to leverage digital history methods.

![box 9, Egypt US Embassy Cairo 1959-1961 Unclassfied Records]({{ site.baseurl }}/assets/images/box9.jpg)

This image shows a network graph of the topical clusters from Box 9 of the Egypt US Embassy Cairo 1959-1961 Unclassified Records. The graph was produced with Dave McClure's textplot program. Dave has a number of excellent posts describing the tool here, and you can also see it in use in Micki Kaufman's Quantifying Kissinger project. Textplot essentially maps how words flow and cluster in a corpus, which can be helpful for identifying the conceptual structure of a set of texts. 

In looking at this textplot, if you zoom in on the far right lower cluster you can see what I believe is the 'anti-colonial' cluster. 

![Far right cluster, box 9, Egypt US Embassy Cairo 1959-1961 Unclassfied Records]({{ site.baseurl }}/assets/images/rhodesiaincairo.jpg)

In this cluster, there's the name Rhodesia, which makes sense because 
of its part in anti-colonial struggles. However, the timing of its appearance surprised me since the only reference I knew of to Rhodesia in Cairo was tied to the break of relations with the UK in 1965 and the later struggles of the 1970s. To investigate further, I used a tool called antconc to search for Rhodesia in these folders. 

![AntConc]({{ site.baseurl }}/assets/images/antconc.jpg)

Using antconc, I discovered a document from the American Embassy in Cairo about the visit of Joshua Nkomo to Cairo in March of 1959, which was around the time that many African liberation movements established offices in Cairo through funding from the UAR government. 

![NARA Doc]({{ site.baseurl }}/assets/images/rhodesiadoc.jpg)

I had previously read one mention of Nkomo in Cairo in an autobiographical article by Helmi Sharawy, who had been an official in the UAR’s African Bureau. However, Sharawy had not written any exact dates.[^1] Thus, finding this document for me represented finding the proverbial needle in the haystack since I had missed it while I was at NARA. These types of discoveries are especially useful for my project, since recreating anti-colonial networks in Cairo has remained difficult with the limited archival sources.

-
[^1]: Helmi Sharawy, "Memories on African liberation (1956 - 1975)" *Pambazuka News* [http://www.pambazuka.org/pan-africanism/memories-african-liberation-1956-1975](http://www.pambazuka.org/pan-africanism/memories-african-liberation-1956-1975)
