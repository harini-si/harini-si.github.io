---
title: "LLaVA Finds Free Lunch: Teaching Human Behavior Improves Content Understanding Abilities Of LLMs"
collection: publications
excerpt: ''
permalink: /publication/bllava
date: 2024-05-02
venue: 'Under Review'
paperurl: 'https://arxiv.org/abs/2405.00942'
website: 'https://arxiv.org/abs/2405.00942'
authors: Somesh Kumar Singh*, Harini S I*, Yaman Kumar Singla*, Veeky Baths, Rajiv Ratn Shah, Changyou Chen, Balaji Krishnamurthy 
header:
  teaser: /images/bllava.png

---
Communication is defined as "Who says what to whom with what effect." A message from a communicator generates downstream receiver effects, also known as behavior. Receiver behavior, being a downstream effect of the message, carries rich signals about it. Even after carrying signals about the message, the behavior data is often ignored while training large language models. We show that training LLMs on receiver behavior can actually help improve their content-understanding abilities. Specifically, we show that training LLMs to predict the receiver behavior of likes and comments improves the LLM's performance on a wide variety of downstream content understanding tasks. We show this performance increase over 40 video and image understanding tasks over 23 benchmark datasets across both 0-shot and fine-tuning settings, outperforming many supervised baselines. Moreover, since receiver behavior, such as likes and comments, is collected by default on the internet and does not need any human annotations to be useful, the performance improvement we get after training on this data is essentially free-lunch. We release the receiver behavior cleaned comments and likes of 750k images and videos collected from multiple platforms along with our instruction-tuning data.


