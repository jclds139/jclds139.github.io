---
title: "PigSense: Structural Vibration-Based Activity and Health Monitoring System
  for Pigs"

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`),
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
  - Yiwen Dong
  - Amelie Bonde
  - Jesse R Codling
  - Adeola Bannis
  - Jinpu Cao
  - Asya Macon
  - Gary Rohrer
  - Jeremy Miles
  - Sudhendu Sharma
  - Tami Brown-Brandl
  - Akkarit Sangpetch
  - Orathai Sangpetch
  - Pei Zhang
  - Hae Young Noh

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: "2023-06-01"

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: "2024-11-07T02:38:43.614938Z"

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
  - article-journal

# Publication name and optional abbreviated publication name.
publication: "*ACM Transactions on Sensor Networks*"
publication_short: "TOSN"

doi: 10.1145/3604806

abstract: Precision Swine Farming has the potential to directly benefit swine health
  and industry profit by automatically monitoring the growth and health of pigs. We
  introduce the first system to use structural vibration to track animals, and the
  first system for automated characterization of piglet group activities, including
  nursing, sleeping, and active times. PigSense uses physical knowledge of the structural
  vibration characteristics caused by pig-activity-induced load changes to recognize
  different behaviors of the sow and piglets. In order for our system to survive the
  harsh environment of the farrowing pen for three months, we designed simple, durable
  sensors for physical fault tolerance, then installed many of them, pooling their
  data to achieve algorithmic fault tolerance even when some do stop working. The
  key focus of this work was to create a robust system that can withstand challenging
  environments, has limited installation and maintenance requirements, and uses domain
  knowledge to precisely detect a variety of swine activities in noisy conditions
  while remaining flexible enough to adapt to future activities and applications.
  We provided an extensive analysis and evaluation of all-round swine activities and
  scenarios from our 1-year field deployment across two pig farms in Thailand and
  the USA. To help assess the risk of crushing, farrowing sicknesses, and poor maternal
  behaviors, PigSense achieves an average of 97.8% and 94% for sow posture and motion
  monitoring, respectively, and an average of 96% and 71% for ingestion and excretion
  detection. To help farmers monitor piglet feeding, starvation, and illness, PigSense
  achieves an average of 87.7%, 89.4%, and 81.9% in predicting different levels of
  nursing, sleeping, and being active, respectively. In addition, we show that our
  monitoring of signal energy changes allows the prediction of farrowing in advance,
  as well as status tracking during the farrowing process and on the occasion of farrowing
  issues. Furthermore, PigSense also predicts the daily pattern and weight gain in
  the lactation cycle with 89% accuracy, a metric that can be used to monitor the
  piglets' growth progress over the lactation cycle.

# Summary. An optional shortened abstract.
summary: ""

tags:
  - Geomcu
  - Journal
  - Pigs project

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: https://dl.acm.org/doi/pdf/10.1145/3604806
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
---