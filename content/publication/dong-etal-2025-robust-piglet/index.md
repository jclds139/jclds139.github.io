---
title: Robust Piglet Nursing Behavior Monitoring through Multi-Modal Fusion of Computer
  Vision and Ambient Floor Vibration

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Yiwen Dong
- Zihao Song
- Jesse R. Codling
- Gary Rohrer
- Jeremy Miles
- Sudhendu Sharma
- Tami Brown-Brandl
- Pei Zhang
- Hae Young Noh

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-11-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-09-11T01:11:27.621060Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Computers and Electronics in Agriculture*'
publication_short: ''

doi: 10.1016/j.compag.2025.110804

abstract: "Nursing is a critical activity during the lactation period of swine farming.
  Continuous monitoring of piglet nursing behavior during the lactation period is
  essential to informing animal caretakers about the health status of piglets to reduce
  the mortality rate, maximize lactational growth, and improve animal welfare. Traditional
  approaches rely on manual observation and wearable devices, which are labor-intensive
  and can cause discomfort to the animals. Recent advancement in computer vision and
  ambient vibration sensing enables non-contact piglet nursing monitoring: The computer
  vision approach captures piglet location but has limited observation of their detailed
  movement due to lighting, resolution, and visual obstruction constraints; the ambient
  vibration sensing approach captures piglet movement patterns but has limited location
  information. In this study, a novel approach to integrate these two complementary
  sensing modalities is developed for robust piglet nursing behavior monitoring during
  the lactation period. This study leverages the state-of-the-art Segment Anything
  Model (SAM) to first convert images into sparse representations of piglet behaviors
  and then combine with ambient vibration to collaboratively infer piglet nursing
  pattern and intensity. This new approach enables piglet nursing monitoring with
  much lower computing and storage requirements than conventional computer vision
  methods, making it more practical for farm settings. Real-world experiments were
  conducted at a pig farm for continuous vision and vibration monitoring of 8 pens
  over 3 farrowing cycles. This study has a 97% accuracy in classifying 5 nursing
  stages, representing a significant 3× and 3.8× error reduction compared to the baseline
  method using only vision or vibration data, respectively. The multi-modal fusion
  approach leads to an efficient, robust, and accurate piglet nursing model that can
  immediately inform caretakers of issues that arise during this crucial time point
  of a piglet's life."

# Summary. An optional shortened abstract.
summary: ''

tags:
- Computer vision
- Multi-modal
- Nursing
- Precision livestock farming
- Structural vibration

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://www.sciencedirect.com/science/article/pii/S016816992500910X'
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
  - geomcu
---
