---
title:
  "Poster Abstract: Leveraging General-Purpose Audio Datasets for Vibration-Based
  Crowd Monitoring in Stadiums"

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`),
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
  - Yen Cheng Chang
  - Jesse Codling
  - Yiwen Dong
  - Jiale Zhang
  - Jiasi Chen
  - Hae Young Noh
  - Pei Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: "2025-05-01"

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: "2025-09-11T01:11:27.598935Z"

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
  - paper-conference

# Publication name and optional abbreviated publication name.
publication:
  "*Proceedings of the 23rd ACM Conference on Embedded Networked Sensor
  Systems*"
publication_short: "SenSys 2025"

doi: 10.1145/3715014.3724022

abstract:
  Crowd monitoring in sports stadiums is important to enhance public safety and improve audience experience. Existing approaches mainly rely on cameras and microphones, which can cause significant disturbances and often raise privacy concerns. In this paper, we sense floor vibration, which provides a less disruptive and more non-intrusive way of crowd sensing, to predict crowd behavior. However, since the vibration-based crowd monitoring approach is newly developed, one main challenge is the lack of training data due to sports stadiums are usually large public spaces with complex physical activities.
  To overcome this challenge, we present Vibration Leverage Audio (ViLA), a vibration-based method that reduces the dependency on labeled data by pre-training with unlabeled cross-modality data. ViLA first pre-trains a model in an unsupervised manner using commonly available audio datasets and then fine-tunes the model with a small amount of labeled vibration data. Our real-world experiments demonstrate that pre-training the vibration model using publicly available audio data (YouTube8M) achieved up to a 4.5× accuracy improvement compared to the model without audio pre-training.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: "https://dl.acm.org/doi/pdf/10.1145/3715014.3724022"
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
  - stadium
  - geomcu
---
