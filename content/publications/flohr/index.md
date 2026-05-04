---
title: "FloHR: Ubiquitous Heart Rate Measurement Using Indirect Floor Vibration Sensing"

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`),
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
  - Jesse R. Codling
  - Jeffrey D. Shulkin
  - Yen-Cheng Chang
  - Jiale Zhang
  - Hugo Latapie
  - Hae Young Noh
  - Pei Zhang
  - Yiwen Dong

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: "2024-10-01"

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: "2025-09-11T01:11:27.586677Z"

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
  - paper-conference

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 11th ACM International Conference on Systems for
  Energy-efficient Buildings, Cities, and Transportation*"
publication_short: "BuildSys 2024"

doi: 10.1145/3671127.3698170

abstract: Heart rate is one of the most critical metrics for human health. Most common
  methods for measuring human heart rate involve body contact, whether from wearable
  devices or manual measurement. However, such devices can cause discomfort to some
  patients. Past work for non-contact or remote heart rate measurement (e.g., camera
  or radio) is often limited by line-of-sight requirements that are not always possible
  in the real-world environment.This paper presents FloHR, an indirect heart rate
  monitoring system for human beings using heartbeat-induced floor vibrations. The
  key insight is that the human body generates a small wave of pressure and sound
  with each heartbeat. These are propagated as vibration through the structures the
  person is in contact with (e.g., a chair) and through the floor. FloHR then detects
  and interprets these small floor vibrations. We developed a highly sensitive vibration
  sensing system and heartbeat pattern modelling to identify these tiny vibrations
  among other body motions and ambient noise.We evaluated FloHR in a real home environment,
  demonstrating an average heart rate error similar to medical device standards on
  the floor near the subjects' chair, and on the order of 10 beats per minute (bpm)
  on the floor 2 meters away from the subject.

# Summary. An optional shortened abstract.
summary: ""

tags:
  - Heart rate
  - Fully-reviewed conference
  - Vibration

# Display this page in a list of Featured pages?
featured: true

# Links
url_pdf: https://dl.acm.org/doi/pdf/10.1145/3671127.3698170
url_slides: slides.pdf

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
  hint: photo
  mode: responsive

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - geomcu
  - hr
---