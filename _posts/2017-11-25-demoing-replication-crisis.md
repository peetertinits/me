---
title: "Discussing replication crisis at TheoLingEst 2017"
header:
categories:
  - talk
  - open-science
tags:
  - replication-crisis
  - talk
  - open-science
  - slides
  - link-collection
---

On Thursday-Friday the conference on theoretical linguistics in Estonia took place. "Theoretical" not so much in the sense of "formal", but general discussions on the theory and what that has to do with the language sciences. This event takes place every four years, and gives a place to talk about theory for people thinking about theory in the language sciences. This time the topic was the impact of the quantitative turn on language theory, so I figured that someone should also talk about the replication crisis and took this job for myself.

This is partly inspired by the [SMLP summer school](https://www.uni-potsdam.de/de/summercampus/e/smlp.html) on statistics in Potsdam. In addition to very involved and high quality teaching of statistics in various shapes and forms, I came back with two new ideas: 1) that worrying about problems with stats does not have to be for a few freaks, but this all can be pretty obvious and convincing when you show it with a few visualizations and interactive tools; 2) - articulated by people who know much better - worrying about proper conduct and replicability is moving towards the mainstream, while ideas can often be old, the social momentum in worrying about this is growing. Based on the show of hands at TheoLingEst 2017 during the talk in the room, around half of the ~40 people in the room were aware of the issues with replicability.

Thus, I took as my purpose to try to give such a demo to linguists with various backgrounds. The examples that I found most easy to show were p-hacking (and the simplicity of this) within the "garden of forking paths", and data peeking or optional stopping when collecting data. Both are on the other hand quite relevant and easy to miss issues when doing your first data analysis. In fact, in linguistics these issues are practically far from solved, both for experimental studies and corpus studies, as the solutions of cross-validation or pre-registering are used in only a few of the studies. It is difficult to talk about these issues without becoming an evangelist for science openness, so I added a bit of that too. Particularly, I liked Daniel Lakens' speculations on how by 2070, the earlier lack of openness in data will seem unbelievable. Nicely put by him on this slide:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">To do real science we need team science. Which means .... sharing both ideas &amp; data! Seems sensible but surprising number of people still afraid of being scooped <a href="https://twitter.com/hashtag/futureofscience?src=hash&amp;ref_src=twsrc%5Etfw">#futureofscience</a> with <a href="https://twitter.com/lakens?ref_src=twsrc%5Etfw">@lakens</a> <a href="https://t.co/ocRRqrQ2Ge">pic.twitter.com/ocRRqrQ2Ge</a></p>&mdash; Caro Rowland (@CaroRowland) <a href="https://twitter.com/CaroRowland/status/928969160117374977?ref_src=twsrc%5Etfw">November 10, 2017</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

All of these topics matter a lot due to limited resources in science, and should do so especially more in even smaller communities (e.g. local communities of linguists, such as the one in Estonia). I've added the points and links I found most useful for such a demo here just in case. Perhaps even better than a demo, Maki Naro has made a nice comic on this here - [Repeat after me](https://thenib.com/repeat-after-me).

## Core research articles

- [John Ioannidis (2005) Why Most Published Research Findings Are False.](http://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.0020124)
- [Joseph P. Simmons, Leif D. Nelson, Uri Simonsohn 2011. False-Positive Psychology: Undisclosed Flexibility in Data Collection and Analysis Allows Presenting Anything as Significant. Psychological Science 22: 11, 1359 - 1366.](https://doi.org/10.1177/0956797611417632)
- [Andrew Gelman & Eric Loken 2013. The garden of forking paths: Why multiple comparisons can be a problem, even when there is no ``fishing expedition'' or ``p-hacking'' and the research hypothesis was posited ahead of time. (Unpublished.)](http://www.stat.columbia.edu/~gelman/research/unpublished/p_hacking.pdf)
- [Open Science Collaboration (2015). Estimating the reproducibility of psychological science. Science, 349.](http://science.sciencemag.org/content/349/6251/aac4716)
- [Munafo et al. 2017. A manifesto for reproducible science](https://www.nature.com/articles/s41562-016-0021)
- [Zwaan et al. 2017. Making replication mainstream](https://www.ncbi.nlm.nih.gov/pubmed/29065933)

## Informal summaries
- [Andrew Gelman (2016) post on replication crisis timeline](http://andrewgelman.com/2016/09/21/what-has-happened-down-here-is-the-winds-have-changed/)
- [Daniel Lakens (2017) on how replication crisis has been technically solved](http://daniellakens.blogspot.com.ee/2017/08/towards-more-collaborative-science-with.html)

## Explanatory materials with visualizations
- [4 demos by Mark Andrews (2017)](https://lawsofthought.github.io/replication-crisis-demos/
)
  - [False discovery ](https://lawsofthought.shinyapps.io/false_discovery/)
  - [Basic p-hacking](https://lawsofthought.shinyapps.io/p_hacking)
  - [Optional stopping](https://lawsofthought.shinyapps.io/optional_stopping)
  - [Statistical Power](https://lawsofthought.shinyapps.io/power_failure)
- Aschwanden 2015. [Science isn’t broken: It’s hell of a lot harder than we give credit for](https://fivethirtyeight.com/features/science-isnt-broken/)
  - [The p-hacking app separately](https://projects.fivethirtyeight.com/p-hacking/)
- Reinhart 2015. [Stopping rules and regression to the mean](https://www.statisticsdonewrong.com/regression.html)
- Yarkoni & Braver 2010. [the capricious nature of p < .05, or why data peeking is evil](https://www.talyarkoni.org/blog/2010/05/06/the-capricious-nature-of-p-05-or-why-data-peeking-is-evil/)
- Schwarzkopf 2016. [On the worthlessness of inappropriate piloting](https://neuroneurotic.net/2016/08/29/on-the-worthlessness-of-inappropriate-piloting/)
- Schwarzkopf 2016. [On the magic of independent piloting](https://neuroneurotic.net/2016/08/30/on-the-magic-of-independent-piloting/)


I've also uploaded the [slides]({{ site.url }}{{ site.baseurl }}/assets/files/slides/Tinits_2017_TheorLing_slides.pdf) if they might be useful. They are (mostly) in Estonian.
