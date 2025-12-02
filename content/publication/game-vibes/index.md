---
title: "GameVibes: Vibration-Based Crowd Monitoring for Sports Games through Audience-Game-Facility
  Association Modeling"

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`),
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
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

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: "2023-11-01"

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: "2024-11-07T02:38:43.587944Z"

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
  - paper-conference

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 10th ACM International Conference on Systems for
  Energy-efficient Buildings, Cities, and Transportation*"
publication_short: "BuildSys 2023"

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

# Summary. An optional shortened abstract.
summary: ""

tags:
  - Stadiums
  - Geomcu
  - Fully-reviewed conference

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: https://dl.acm.org/doi/pdf/10.1145/3600100.3623750
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - geomcu
  - stadium
---