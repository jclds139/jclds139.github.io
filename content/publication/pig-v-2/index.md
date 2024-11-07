---
title: 'PigV2: Monitoring Pig Vital Signs through Ground Vibrations Induced by Heartbeat
  and Respiration'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Yiwen Dong
- Jesse R Codling
- Gary Rohrer
- Jeremy Miles
- Sudhendu Sharma
- Tami Brown-Brandl
- Pei Zhang
- Hae Young Noh

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-11-07T02:38:43.622911Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 20th ACM Conference on Embedded Networked Sensor
  Systems*'
publication_short: ''

doi: 10.1145/3560905.3568416

abstract: Pig vital sign monitoring (e.g., estimating the heart rate (HR) and respiratory
  rate (RR)) is essential to understand the stress level of the sow and detect the
  onset of parturition. It helps to maximize peri-natal survival and improve animal
  well-being in swine production. The existing approach mainly relies on manual measurement,
  which is labor-intensive and only provides a few points of information. Other sensing
  modalities such as wearables and cameras are developed to enable more continuous
  measurement, but are still limited due to animal discomfort, data transfer, and
  storage challenges. In this paper, we introduce PigV2, the first system to monitor
  pig heart rate and respiratory rate through ground vibrations. Our approach leverages
  the insight that both heartbeat and respiration generate ground vibrations when
  the sow is lying on the floor. We infer vital information by sensing and analyzing
  these vibrations. The main challenge in developing PigV2 is the overlap of vital-
  and non-vital-related information in the vibration signals, including pig movements,
  pig postures, pig-to-sensor distances, and so on. To address this issue, we first
  characterize their effects, extract their current status, and then reduce their
  impact by adaptively interpolating vital rates over multiple sensors. PigV2 is evaluated
  through a real-world deployment with 30 pigs. It has 3.4% and 8.3% average errors
  in monitoring the HR and RR of the sows, respectively.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Fully-reviewed conference
- Heart rate
- Pigs project

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: https://dl.acm.org/doi/pdf/10.1145/3560905.3568416
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
    - pigs
    - hr
    - geomcu
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
