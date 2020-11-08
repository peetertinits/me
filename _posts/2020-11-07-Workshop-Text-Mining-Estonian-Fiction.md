---
title: "Using Estonian Fiction texts to learn simple text analysis in R 2"
header:
categories:
  - teaching
tags:
  - teaching
---

Using Estonian Fiction texts to learn simple text analysis in R 2
========================================

As part of the studies in Digital Methods and Contemporary datasets we learned about using R and Tidyverse to do simple text processing, in this case on longer texts. We looked at Tõde ja õigus, a canonical text in Estonia by A.H. Tammsaare and used tidytext to count and locate tokens, find ngrams and content words, and distinguishing keywords. We used a set of Estonian fiction texts from an [open collection](https://datadoi.ee/handle/33/76) to study word usage across different works.

The materials are posted online on [github](https://github.com/peeter-t2/TM_SV_TartuFall2020). Some graphs made:

## Locations of popular 5-grams in "Tõde ja õigus. 1 kd."
![Locations of popular 5-grams in "Tõde ja õigus. 1 kd."]({{ site.url }}{{ site.baseurl }}/assets/images/viisgrammid.png)
Five-grams were calculated with unnest tokens

## Distinguishing keywords of chapters 1-10 in "Tõde ja õigus. 1 kd."
![Distinguishing keywords of chapters 1-10 in "Tõde ja õigus. 1 kd]({{ site.url }}{{ site.baseurl }}/assets/images/tammsaare1_ptk1-10_eristav.png)
Words were lowercased, proper names kept in. Comparison made across all 39 chapters.

## Frequency of forest, land, city in Estonian Fiction books.
![Frequency of forest, land, city in Estonian Fiction books.]({{ site.url }}{{ site.baseurl }}/assets/images/mets_maa_linn.png)

Frequency of forest, land, and city related words was calculated as a proportion of tokens. Words beginning with ^mets, ^maa, ^linn were used.
