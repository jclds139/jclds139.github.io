---
title: 'GameVibes: Vibration-based Crowd Monitoring for Sports Games through Audience-Game-Facility
  Association Modeling'
authors:
- Yiwen Dong
- Yuyan Wu
- Jesse R Codling
- Jatin Aggarwal
- Peide Huang
- Wenhao Ding
- Hugo Latapie
- Pei Zhang
- Hae Young Noh
date: '2023-11-01'
publishDate: '2024-08-15T21:32:55.120325Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 10th ACM International Conference on Systems for
  Energy-Efficient Buildings, Cities, and Transportation*'
doi: 10.1145/3600100.3623750
abstract: Crowd monitoring involves tracking and analyzing the behavior of large groups
  of people in large-scale public spaces, such as sports games. In sports stadiums,
  understanding audience reactions to the games and their distribution around the
  public facilities is important for ensuring public safety and security, enhancing
  the game experience, and improving crowd management. Recent crowd-crushing incidents
  (e.g., Kanjuruhan Stadium disaster, Seoul Halloween Stampede) have caused 100+ deaths
  in a single event, calling for advancements in crowd monitoring methods. Existing
  monitoring approaches include manual observation, wearables, video-, audio-, and
  WiFi-based sensing. However, few meet the practical needs due to their limitations
  in cost, privacy protection, and accuracy. In this paper, we introduce GameVibes,
  a novel method for crowd behavior monitoring using crowd-induced floor vibrations
  to infer audience reactions to the game (e.g., clapping, stomping, dancing) and
  crowd traffic (i.e., the number of people entering each door). The main benefits
  of GameVibes are that it allows continuous, fine-grained crowd monitoring in a cost-effective
  and non-intrusive way and is perceived as more privacy-friendly. Unlike monitoring
  an individual person, crowd monitoring involves understanding the overall behavior
  of a large population (typically more than 1,000), leading to high uncertainty in
  the vibration data. To overcome the challenge, we first establish the game and facility
  association to inform the context of crowd behaviors, including 1) game associations
  (temporal context) between the crowd reaction and the game progress and 2) facility
  associations (spatial context) between the crowd traffic and facility layouts. Then,
  we formulate the crowd monitoring problem by converting the conceptual graph of
  the audience-game-facility association into probabilistic game/facility association
  models. Through these models, GameVibes first learns the latent representations
  of the game progress and facility layout through neural network encoders, and then
  integrates heterogeneous game/facility information and vibration data to estimate
  crowd behaviors. This mitigates the estimation error due to the uncertainty in vibration
  data. To evaluate our approach, we conduct 6 real-world deployments for NCAA Pac-12
  games at Stanford Maples Pavilion. Our results show that GameVibes achieves a 0.9
  F-1 score in crowd reaction monitoring and 9.3 mean absolute error in crowd traffic
  estimation, which correspond to 10% and 12.2% error reduction, respectively, compared
  to the baseline methods without context-specific information.
tags:
- Fully-Reviewed Conference
- GeoMCU
- Stadiums
url_pdf: https://dl.acm.org/doi/pdf/10.1145/3600100.3623750
---
