---
title: "Neuro-symbolic Meta Reinforcement Learning for Trading"
collection: publications
excerpt: ''
permalink: /publication/logic_meta_rl
date: 2023-01-15
venue: 'Paper accepted at Multimodal AI for Financial Forecasting Workshop at AAAI '
paperurl: 'https://arxiv.org/abs/2302.08996'
authors: S I Harini, Gautam Shroff, Ashwin Srinivasan, Prayushi Faldu, Lovekesh Vig
header:
  teaser: /images/trading.png

---
We model short-duration (e.g. day) trading in financial markets as a sequential decision-making problem under uncertainty, with the added complication of continual concept-drift. We, therefore, employ meta reinforcement learning via the RL2 algorithm. It is also known that human traders often rely on frequently occurring symbolic patterns in price series. We employ logical program induction to discover symbolic patterns that occur frequently as well as recently, and explore whether using such features improves the performance of our meta reinforcement learning algorithm. We report experiments on real data indicating that meta-RL is better than vanilla RL and also benefits from learned symbolic features.


