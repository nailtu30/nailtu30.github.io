---
title: "Tackling Multiplayer Interaction for Federated Generative Adversarial Networks"
collection: publications
category: Edge-Cloud-Synergy-AI
permalink: /publication/2024-08-05-Tackling-Multiplayer-Interaction-for-Federated-Generative-Adversarial-Networks
excerpt: 'We propose Oasis, a multiplayer-oriented federated GAN training system that addresses the issues of vanishing gradient and mode collapse.'
date: 2024-08-05
venue: 'IEEE Transactions on Mobile Computing'
# slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10623396'
citation: 'Chuang Hu, <b>Tianyu Tu</b>, Yili Gong, Jiawei Jiang, Zhigao Zheng, Dazhao Cheng.'
---

Generative Adversarial Networks (GANs) have become predominant in mobile computing for their ability to generate data. The concern for data privacy has made it arduous to collect large-scale datasets for GAN training on centralized servers. Federated Learning (FL) has emerged as a promising solution to address data privacy concerns. In this paper, we propose Oasis, a multiplayer-oriented federated GAN training system. We present a motivation, highlighting the Nash Equilibrium (NE) shift in vanilla federated GANs, exacerbated by data heterogeneity, leading to poor training performance with issues of vanishing gradient and mode collapse. To address mode collapse, Oasis extracts privacy-preserving data representations and generates a similarity table for clustering clients. Each group independently trains a GAN model and conducts distribution and fusion. By introducing a coordinator, Oasis generalizes intra-group games into Separable Zero-sum Multiplayer Games to tackle vanishing gradient. Thus, Oasis considers the overall federated GAN training as Group-wise Separable Zero-sum Multiplayer Games. Practically, we evaluate our theoretical results both on a hardware prototype and in a simulated environment. Evaluation results demonstrate the effectiveness of Oasis, with an average improvement of 23.13% and 26.33% in terms of FID and NDB/K respectively, compared to three state-of-the-art FL approaches over three datasets.