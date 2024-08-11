---
title: "Measuring And Improving Persuasiveness Of Generative Models"
collection: publications
excerpt: ''
permalink: /publication/transsuasion
date: 2024-05-22
venue: 'Under Review'
website: 'https://behavior-in-the-wild.github.io/measure-persuasion.html'
authors: Somesh Singh*, Yaman K Singla*, Harini S I*, Balaji Krishnamurthy
header:
  teaser: /images/transsuasion.png

---
Effective communication necessitates meticulous crafting of messages to elicit
desired responses from recipients. We introduce transsuasion (trans = carrying
across, suasion = the act of persuading), a novel task of transforming non-persuasive
language into persuasive content while preserving semantic meaning. This ap-
proach extends beyond natural language generation or popularity prediction to
directly influence behavioral outcomes. To construct data for transsuasion, we lever-
age natural experiments, utilizing pairs of tweets from the same user, posted in close
temporal proximity, with similar semantic content but divergent wording and sig-
nificantly different like counts. Given such pairs, we investigate consistent patterns
determining which version garners more likes and explore methods to transsuade
the lower-performing version to the higher-performing one. Our findings indicate
that Large Language Models (LLMs) outperform random baselines in this task, with
persuasiveness correlating positively with model size. Notably, targeted training
using synthetic and natural datasets significantly enhances smaller models’ persua-
sive capabilities, challenging scale-dependent assumptions. In response to growing
concerns about the societal impacts and risks of LLMs, quantifying and monitoring
their persuasive power becomes crucial. To address this need, we introduce Per-
suasionBench and PersuasionArena, the first benchmark and arena containing
a battery of tasks to measure the persuasion ability of generative models auto-
matically. Using these frameworks, we benchmark the performance of traditional
LLMs and our newly developed models for persuasiveness. We invite the commu-
nity to explore and contribute to PersuasionArena and PersuasionBench, available
at https://behavior-in-the-wild.github.io/measure-persuasion, to ad-
vance our understanding of AI-driven persuasion and its societal implications.


