---
title: "VibraFarrow: Pig Farrowing Time Prediction Using Ambient Floor Vibrations"

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`),
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
  - Jinpu Cao
  - Larry Collin Marshall
  - Jesse R Codling
  - Sudhendu Raj Sharma
  - Tami Brown-Brandl
  - Martin Fischer
  - Pei Zhang
  - Hae Young Noh
  - Yiwen Dong

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: "2025-11-01"

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: "2025-12-02T17:10:13.972534Z"

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
  - paper-conference

# Publication name and optional abbreviated publication name.
publication:
  "*Proceedings of the 12th ACM International Conference on Systems for
  Energy-efficient Buildings, Cities, and Transportation*"
publication_short: ""

doi: 10.1145/3736425.3772100

abstract:
  "Farrowing, the onset of parturition in mother pigs (i.e., sows), is a high-risk
  period for both the sow and her newborn piglets. Early and accurate prediction of
  farrowing time, along with monitoring indicators such as vital signs and pre-farrowing
  behaviors, enables timely assistance and can lead to lower stillbirth rates. However,
  existing methods have limitations: camera-based systems require constant lighting
  that disrupts pigs' circadian rhythms, while wearable sensors can cause discomfort
  to pigs and are prone to be damaged.We introduce VibraFarrow, a novel non-intrusive
  vibration sensing system that models pig-induced floor vibration data collected
  from the built environments to predict farrowing time. Specifically, VibraFarrow
  predicts whether a sow will farrow within the next 20 hours, enabling contact-free,
  long-term tracking of farrowing-related behaviors for pigs. The key challenge in
  developing VibraFarrow is the uncertainty of pre-farrowing behaviors embedded in
  the long-term vibration time series. First, pre-farrowing behaviors exhibit highly
  variable timing and duration, occurring intermittently and mixed with ambient noises,
  which complicates feature extraction over time. Second, the types and patterns of
  pre-farrowing behavior are uncertain, leading to unreliable predictions using a
  fixed set of explicit activities. To address the first challenge, VibraFarrow introduces
  Hierarchical Adaptive Window Selection (HAWS), a hierarchical method that adaptively
  selects time windows ranging from hours, minutes, to seconds and extracts farrowing-related
  features from long-term ambient vibration data. Furthermore, to overcome the uncertainty
  of pre-farrowing behavior patterns and types, VibraFarrow allows flexibility in
  extracting implicit indicators that are representative of pre-farrowing behaviors
  for specific time windows through unsupervised clustering. Finally, VibraFarrow
  fuses the implicit behavior indicators and other expert-defined features (e.g.,
  heart and respiration rates) extracted by HAWS for farrowing time prediction.We
  deployed our system on a real-world farm for seven months, monitoring 18 farrowing
  events and collecting 384 hours of vibration data. The system achieved a weighted
  F1-score of 0.735, surpassing the baseline by up to 20%. This improvement demonstrates
  floor vibration sensing as an effective, non-intrusive approach for farrowing prediction,
  with broader implications for occupant health and wellness management in built environments."

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: "https://dl.acm.org/doi/pdf/10.1145/3736425.3772100"
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
  - pigs
  - geomcu
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
