---
title: "How to make a (miniature) artificial language?"
header:
categories:
  - Artificial language experiments
  - How-to
tags:
  - R
  - data
---

Under construction

A subjective intro, but can still be useful

One research paradigm that I have been involved in applying a few times, and that is becoming a common toolkit in certain areas of linguistics, is an artificial language learning experiment. The main idea is that you provide participants with a (miniature) artificial language, and have them learn it, use it, or do some tasks with it in a controlled environment. By observing how exactly they do this, and what kinds of results emerge in controlled circumstances for this well-designed miniature language, we could arguably learn about aspects of how natural languages behave. There is a nice overview of some of these experiments for example in [(Tamariz 2017)](#myfootnote1).

It can be used for various types of questions, but needs a general set of tools for it.
Often the language itself is just a tool that's in the background - so how to make this tool`?


There are a number of considerations that go into making these experiments and doing them well - one of them is the shape of a language itself. As I have done this a few times now, and this isn't something for which good guides are available or perhaps can even be made, I thought I would walk through the steps that go into making a language that can work in an artificial language experiment.


- general overviews http://www.replicatedtypo.com/experiments-in-communication-pt-1-artificial-language-learning-and-constructed-communication-systems/1520.html


## Step 1. Purpose of the language

The very first step is to think about the purpose of the language and the role it should play in the experiment. Should people be able to learn this in the time given in the experiment? Should they be able to write it, or speak it themselves, or merely recognize it when spoken? Should they just be able to choose between a few given options?

There are experiments that have used various sorts - for example + refs
[Kirby, Cornish, Smith 2008](#myfootnote2)


sometimes it can be a main thing...

often it's gonna be a background feature that you really want to get done quickly and easily...



### The procedure of language learning

If they are expected to learn it to some degree of competence, then it matters also a lot, how the language is presented at first, what is the procedure for language learning?


## Set of phonemes

http://web.phonetik.uni-frankfurt.de/upsid_info.html

https://en.wikipedia.org/wiki/Consonant#Most_common

https://www.quora.com/What-are-the-most-common-phonemes-among-all-language



### Native language connections

That they can't hear the difference, so pointless...

An easy example What for europeans is /l/ and /r/ might be just one difficult to separate sound for others

## Base vocabulary



### Systematicities within that vocabulary

## Phonotactics

why etc

https://phonotactic.drupal.ku.edu/

- http://corpustools.readthedocs.io/en/latest/phonotactic_probability.html
- http://www.iphod.com/calculator/
- http://linguistics.ucla.edu/people/hayes/BLICK/
- https://phonologicalcorpustools.github.io/CorpusTools/
- http://linguistics.ucla.edu/people/hayes/BLICK/
- https://wiki.bcs.rochester.edu/HlpLab/PsycholinguisticsResources
- http://www.iphod.com/
- https://gist.github.com/ElGatoLoco/6593afc041eaa4df2f9028259ef3d0e7
- https://pypi.python.org/pypi/django-phonotactics/0.1.2
- http://www.phonotactics.ml/
- http://www.people.ku.edu/~mvitevit/PhonoProbHome.html
- https://phonotactic.drupal.ku.edu/
- http://www.bncdnet.ku.edu/cml/info_ccc.vi
-

CVCVCV could be a justified phonotactics based on frequencies in languages - see for refs in my master's dissertation perhaps...


### Native language


## Within language relations,

can use hamming or levenstein at the very start to defend against accidental similarities...



## Text to speech


for CVCVCV - the speech processor could be trained for this... for some reason fluent speaking needs to consider more than one character at the time, so CVCV works nicely..

- http://mary.dfki.de/download/index.html
- https://github.com/marytts/marytts/issues/434
- https://www.academia.edu/19812397/A_Phonetic_Transcription_System_for_the_Shona_Languge
- https://github.com/HaraldBerthelsen/voice-stts-sv-hb-hsmm
- https://github.com/marytts/marytts/wiki/MaryInterface
- http://mary.dfki.de:59125/
- http://www.dev.voxforge.org/projects/Main/wiki/TextToSpeech
- http://espeak.sourceforge.net/languages.html
- https://github.com/marytts/marytts-txt2wav

can also share the altered py file perhaps to go through a csv list...


https://en.wikipedia.org/wiki/Oromo_language#Consonant_and_vowel_phonemes
https://en.wikipedia.org/wiki/Swedish_phonology#Consonants

https://en.wikipedia.org/wiki/Turkish_phonology#Consonants
- good to use the phonotactics that the synthesizer has...



### Refs

<a name="myfootnote1">1</a>: Footnote content goes here
<a name="myfootnote2">2</a>: Footnote content goes here




![The gender of speakers by scene in the last act of Lenz's Hofmeister]({{ site.url }}{{ site.baseurl }}/assets/images/Bechdel_Akt5_Hofmeister.png)
