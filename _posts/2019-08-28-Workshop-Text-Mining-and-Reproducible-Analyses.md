---
title: "Text mining in R and reproducible research"
header:
categories:
  - workshop
tags:
  - workshop
---

Text mining in R and reproducible research
========================================

As part of the summer school [Digital Methods in Humanities and Social Sciences](https://digitalmethods.ut.ee/2019) in the University of Tartu, I gave a workshop on [Text mining in R and reproducible research](https://github.com/peeter-t2/TM-TartuSummer2019). The workshop aimed to give the basics of tidyverse in R and how to use it, and then give an intro to simple text mining techniques. We used two datasets as examples: 1) the [Billboard Hot 100](https://en.wikipedia.org/wiki/Billboard_Hot_100) data set [shared by walkerkq](https://github.com/walkerkq/musiclyrics), 2) The TED talks transcripts made into a [dataset](https://www.kaggle.com/goweiting/ted-talks-transcript) by Wei T.

The materials are posted online on [github](https://github.com/peeter-t2/TM-TartuSummer2019). Some graphs made:

## Productive years of top artists
![Productive years of top artists]({{ site.url }}{{ site.baseurl }}/assets/images/artist_productive_years.png)
Line drawn from first year in the billboards to the last year in the billboards.

## Sentiments in Aretha Franklin's songs
![Sentiments in Aretha Franklin's songs]({{ site.url }}{{ site.baseurl }}/assets/images/franklin_sents.png)
Done using the Bing sentiment lexicon

## The median TED talk
![The median TED talk]({{ site.url }}{{ site.baseurl }}/assets/images/median ted talk.png)
The median location for each word was calculated, and for each 10% quantile, top frequent words were plotted.


> The increasing availability of textual data gives new opportunities for humanities and social sciences that we are only beginning to explore. The nature of the data can vary quite a bit ranging from old digitized newspapers to Twitter or forum posts that are born and live digitally. Provided that we can access the data, they allow quite diverse questions to be answered.

> In this 5-hour tutorial, we will learn the basics of text mining in R following the tidyverse principles. R is a computing environment for statistical analysis and graphics that allows analyses performed to be easily reproduced later and by other researchers. Tidyverse is an opinionated set of packages that aim to make using R easy to read and learn.

> Using reproducible analyses allows humanities and social sciences to increase transparency in the research process, make it easier to collaborate, and and easier to build on earlier research. Movements among researchers have shown the benefits of Open Science and Open Research Practices for our scientific knowledge about the world.

> What exactly: We will use tidytext and ggplot2 packages to make simple visualizations of texts. We will compare word frequencies, do simple sentiment analysis, and find keywords in texts. We will explore these on novels, dramas, and/or song lyrics in English. Exploring your own texts is a possibility. The tutorial aims to give the basic techniques that would help you get started on research project of your own.


> Workshop takes place in three sessions in Lossi 3-406:
> - **10:45 – 12:45 Introduction. Basic R, tidyverse & ggplot2.**
> - 12:45 – 14:00 Lunch break
> - **14:00 – 15:30 Text processing in R. Words in text, keywords, sentiments.**
> - 15:30 – 16:00 Coffee break
> - **16:00 – 17:30 Text processing in R. Another dataset. Reproducible markdown.**
