---
title: "Text Mining 101 with Tidytext"
header:
categories:
  - teaching
  - text-mining
tags:
  - R
  - data
---

Text Mining 101 with Tidytext
=============================

Back in September, I gave an introductory workshop on Digital Humanities and text mining in the [Summer School of Baltic Enlightenment and its Inheritance](https://sisu.ut.ee/mdad/sommerschule-die-baltische-aufkl%C3%A4rung-und-ihr-erbe). The audience was German philology undergraduate and graduate students with little knowledge of either of the topics.

We discussed with the organizers for a while how this could be handled, from varying corpora related to Enlightenment era in the Baltic countries to inspiring questions that this could provide. My main goal was to provide them with hands on experience that they could be able to develop and explore later on themselves.

While there are a variety of tools available for text mining and visualization purposes, they suffer from poor interoperability - most tools seem to last for only a few years, and often run into major issues whenever you want to do something a bit more specific than they were initially meant for. Giving a hands-on intro to text mining however seems as necessarily quite separate from whatever tools could be used.

Over the years, I've grown to use and rely on R for various data processing purposes, particularly for it's plug & play feature - it is easy to install and through script files (and an internet for installing libraries) any analysis steps can be easily retraced in another computer. However first steps in R can be tricky, especially with little or no programming experience.

In preparing for the lessons, I was delighted to find [Tidytext](http://tidytextmining.com/) a [tidyverse](https://www.tidyverse.org/)-driven text mining library for R. The commands are so simple yet so powerful that I felt a loss for having spent all that time learning and inventing various ways text can be processed in R.

I fully support David Robinson's advice [to teach tidyverse to beginners](http://varianceexplained.org/r/teach-tidyverse/), and I can say that I tried an empirical test for it. Instead of explaining R, the loops and the functions, I just explained the basic commands in #tidytext and where the results would appear in RStudio. While getting R to work was still an issue, I found that this approach was not at all impossible, - and while in 3 hours it is difficult to get to the details, most participants were successfully able to produce the workshop images in their own computers.

The training materials were designed closely following Julia Silge's and David Robinson's [book on tidytext](http://tidytextmining.com/) and related online materials by others. With tidytext, the actual text processing seems easy - so the task to a tutor would then be to find interesting tasks to perform. In our seminar, we did a Bechdel test on an 18th century novel The Tutor ([Hofmeister](https://de.wikipedia.org/wiki/Der_Hofmeister)) by Jakob Lenz. The results were not very enlightened - only 3/34 scenes included at least two women, and in only one of them was the conversation not about a man. Once is enough for a pass though.

Code and materials of the workshop is available in [github](https://github.com/peeter-t2/DH-workshop-BAIE17). We used Gutenberg texts to look at simple word frequencies, compare texts, find [tf-idf](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) keywords and sentiment analysis across different books (in English) and within Lenz's play (in German).

![The gender of speakers by scene in the last act of Lenz's Hofmeister]({{ site.url }}{{ site.baseurl }}/assets/images/Bechdel_Akt5_Hofmeister.png)
