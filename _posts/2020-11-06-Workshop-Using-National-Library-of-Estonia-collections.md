---
title: "Workshop: Using National Library of Estonia text collections"
header:
categories:
  - workshop
tags:
  - workshop
---

Workshop: Using National Library of Estonia text collections
========================================

I gave a workshop in the Seminar of Digital Archives on the approach we are building at the National Library of Estonia to access text collections. The event was preceded by a [day of talks](https://www.nlib.ee/et/digihumanitaaria-ja-digiarhiiv-2020#nordplus) at the Digital Humanities and Digital Archives with interesting talks on this topic.

- 11.00-12.00 Data journey: insights and experiences  - Mahendra Mahey (British Library) [some twitter screenshots](https://twitter.com/yrgsupp/status/1323918075327111168), [some more twitter screenshots](https://twitter.com/AndresKarjus/status/1323921173944684545)
- 12.00-13.00 GLAM Workbench and Jupyter notebooks to explore digital collections - Tim Sherrat (University of Canberra) [some twitter screenshots](https://twitter.com/yrgsupp/status/1323932961318854656)
- 13.00-14.00 LUNCH
- 14.00-15.00 GLAMalytics for GLAMerous application - Max Schich (Tallinn University) [some twitter screenshots](https://twitter.com/yrgsupp/status/1323961043325014019)
- 15.00-16.15 How to put culture on a map? (hands-on workshop) - Evelyn Uuemaa (University of Tartu) [some twitter screenshots](https://twitter.com/yrgsupp/status/1323981498958204928)
- 16.15-16.30 COFFEE BREAK
- 16.30-17.30 Working with maps at scale using Computer Vision and Jupyter notebooks (hands-on workshop) - Daniel van Strien (British Library) [some twitter screenshots](https://twitter.com/yrgsupp/status/1324001057035427841)

The workflow used at the moment relies on Jupyter Notebooks opened on the same servers as the text files, and a few custom R commands to retreive the texts in a clean format. The custom R commands are presented as a package on [github](https://github.com/peeter-t2/digar.txts). The Jupyter Notebooks work with a username on the servers, we used temporary usernames at the workshop, more permanent usernames can be got when asking us.

![Jypiter access example 1]({{ site.url }}{{ site.baseurl }}/assets/images/jupyter1.png)
![Jypiter access example 2]({{ site.url }}{{ site.baseurl }}/assets/images/jupyter2.png)
![Jypiter access example 3]({{ site.url }}{{ site.baseurl }}/assets/images/jupyter3.png)

The first tests look promising, texts can be retrieved fairly quickly and analysed with common tools.


The workshop materials were posted on [hackmd](https://hackmd.io/OotxTpFhRbCeSylT4RbGVw?view). Some graphs made:

## Georg Lurich vs Konrad Mägi - distinguishing words
![Georg Lurich vs Konrad Mägi - distinguishing words]({{ site.url }}{{ site.baseurl }}/assets/images/lurich_magi.png)
The distinguishing words between texts containing Georg Lurich and Konrad Mägi 1886-1940.

## Steam, Electricity, Horses in Estonia 1886-1940
![Productive years of top artists]({{ site.url }}{{ site.baseurl }}/assets/images/aur_elekter_hobu.png)
The proportion of texts in Postimees 1886-1940 containing words related to steam, electricity, and horses.

## Electricity and Appliances in Estonia 1886-1940
![Sentiments in Aretha Franklin's songs]({{ site.url }}{{ site.baseurl }}/assets/images/elektrigraafik1.png)
Some selected examples of words containing "elekt" in Estonian and their distribution over time.


> Sessioon A: RR digitaalarhiivis DIGAR olevate tekstide kasutamine (hands-on workshop)
Mida saab teha digitaalsete tekstidega? Ligipääs Digari Eesti artiklitele avatud koodi kaudu. Lihtsam tekstitöötlus ja selle tulemused R-is.
Kasutame RStudiot, juhend selle paigaldamiseks saadetakse registreerunutele.
Töötuba ei eelda varasemaid programmeerimisoskusi. Sellest hoolimata kirjutame aga ise töötoas koodi.
