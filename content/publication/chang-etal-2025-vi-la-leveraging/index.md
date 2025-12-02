---
title: "ViLA: Leveraging General-Purpose Audio for Training Vibration-Based Stadium
  Crowd Monitoring Models"

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`),
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
  - Yen Cheng Chang
  - Jesse Codling
  - Yiwen Dong
  - Jiale Zhang
  - Hae Young Noh
  - Pei Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: "2025-11-01"

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: "2025-12-02T17:10:13.950869Z"

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
  - paper-conference

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 12th ACM International Conference on Systems for
  Energy-efficient Buildings, Cities, and Transportation*"
publication_short: ""

doi: 10.1145/3736425.3770100

abstract: Crowd monitoring in sports stadiums is important to enhance public safety
  and improve audience experience. Existing approaches mainly rely on manual observation,
  cameras, and microphones, which can be disruptive and often raise privacy issues.
  Recently, floor vibration sensing has emerged as a less disruptive and more non-intrusive
  method for crowd monitoring in sports stadiums. However, because vibration-based
  crowd monitoring is newly developed, open-source datasets are lacking, making it
  challenging to develop data-driven models.In this paper, we introduce Vibration
  Leverages Audio (ViLA), a vibration-based crowd monitoring method that reduces the
  reliance on labeled data by pre-training with unlabeled cross-modality data. Specifically,
  ViLA is first pre-trained on general-purpose audio data in an unsupervised manner,
  and then fine-tuned with a limited amount of labeled vibration data in sensing domains.
  Through this approach, ViLA learns general spectral pattern representations from
  audio, then adapts this knowledge to vibrations. By leveraging general-purpose audio
  datasets, ViLA reduces the reliance on large quantities of domain-specific vibration
  data. This is particularly important in sensing environments characterized by high
  data variance and limited sensing durations, such as sports games. Our real-world
  experiments demonstrate that pre-training the vibration model using publicly available
  audio data (YouTube clips) achieved up to a 5.8X error reduction compared to the
  model without audio pre-training.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: "https://dl.acm.org/doi/pdf/10.1145/3736425.3770100"
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

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.