---
title: "Long-Term Ad Memorability: Understanding & Generating Memorable Ads"
collection: publications
permalink: /publication/longterm_mem
excerpt: ''
date: 2023-09-24
venue: 'Under Review'
website: 'https://behavior-in-the-wild.github.io/memorability.html'
paperurl: 'https://arxiv.org/abs/2309.00378'
authors: Harini S I*, Somesh Singh*, Yaman K Singla*, Aanisha Bhattacharyya, Veeky Baths, Changyou Chen, Rajiv Ratn Shah, Balaji Krishnamurthy
header:
  teaser: /images/mem2.png
---
Marketers spend billions of dollars on advertisements but to what end? At the time of purchase, if customers cannot recognize the brand for which they saw an ad, the money spent on the ad is essentially wasted. Despite its importance in marketing, until now, there has been no study on the memorability of ads in the ML literature. Most studies have been conducted on short-term recall (<5 mins) on specific content types like object and action videos. On the other hand, the advertising industry only cares about long-term memorability, and ads are almost always highly multimodal, depicting a story through its different modalities. With this motivation, we release the first large-scale memorability dataset, LAMDBA, consisting of 1749 participants and 2205 ads covering 276 brands. Running statistical tests over different participant subpopulations and ad types, we find many interesting insights into what makes an ad memorable. For e.g., we find that brands that use commercials with fast-moving scenes are more memorable than those with slower scenes (p=8e-10) and that people who use ad-blockers remember fewer ads than those who don't (p=5e-3). Next, to simulate the memorability of marketing materials for a particular audience, we present a novel model, Henry, trained to leverage real-world knowledge of LLMs and visual knowledge to predict the memorability. We test Henry on all the prominent memorability datasets in literature (both images and videos) and achieve state-of-the-art performance across all of them. Henry shows strong generalization showing better results in 0-shot on unseen datasets. Next, we propose the task of memorable ad generation and release a large-scale ad dataset, UltraLAMBDA, consisting of 4 million ads with their Henry-assigned memorability scores. We show that aligning Henry to generate memorable content improves memorability scores by more than 25%.


