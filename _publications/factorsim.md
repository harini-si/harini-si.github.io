---
title: "FactorSim: Generative Simulation via Factorized Representation"
collection: publications
excerpt: ''
permalink: /publication/factorsim
date: 2024-05-22
venue: 'Under Review'
website: 'https://cs.stanford.edu/~sunfanyun/factorsim/'
authors: Fan-Yun Sun, Harini S I, Angela Yi, Yihan Zhou, Alex Zook, Jonathan Tremblay, Logan Cross, Jiajun Wu, Nick Haber 
header:
  teaser: /images/factorsim.png

---
Generating simulations to train intelligent agents in game-playing and robotics from natural language input, from user input or task documentation, remains an open-ended challenge. Existing approaches focus on parts of this challenge, such as generating reward functions or task hyperparameters. Unlike previous work, we introduce FACTORSIM that generates full simulations in code from language input that can be used to train agents. Exploiting the structural modularity specific to coded simulations, we propose to use a factored partially observable Markov decision process representation that allows us to reduce context dependence during each step of the generation. For evaluation, we introduce a generative simulation benchmark that assesses the generated simulation code’s accuracy and effectiveness in facilitating zero-shot transfers in reinforcement learning settings. We show that FACTORSIM outperforms existing methods in generating simulations regarding prompt alignment (i.e., accuracy), zero-shot transfer abilities, and human evaluation. Wealso demonstrate its effectiveness in generating robotic tasks.


