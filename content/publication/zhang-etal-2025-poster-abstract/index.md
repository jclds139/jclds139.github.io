---
title: "Poster Abstract: On-Shelf Weight Difference Estimation through Active Vibration
  Sensing"

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`),
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
  - Jiale Zhang
  - Yuyan Wu
  - Jesse Codling
  - Julia Gersey
  - Adeola Bannis
  - Carlos Ruiz Dominguez
  - Ke Sun
  - Pei Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: "2025-05-01"

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: "2025-05-07T16:55:00.074308Z"

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
  - paper-conference

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 23rd ACM Conference on Embedded Networked Sensor
  Systems*"
publication_short: "SenSys 2025"

doi: 10.1145/3715014.3724047

abstract: Weight difference estimation is crucial in various applications, particularly for identifying items being picked up and put back when people interact with the shelf while shopping in autonomous stores, ensuring precise cost estimation. However, the conventional approach of estimating weight changes requires specialized weight-sensing shelves, which are densely deployed weight scales, incurring intensive sensor consumption and maintenance costs. Prior works explored the vibration-based weight sensing method, but they are limited to the object that can generate vibration through motion. This work demonstrates a system leveraging active vibration sensing for weight difference estimation on shelves at different locations. The main intuition of the system is that the weight placed on the shelf influences the dynamic vibration response of the shelf, thus altering the shelf vibration patterns. Our system achieves a mean absolute error 9.23 grams and mean absolute percentage error 7.9% on the real-store shelf layout.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: "https://dl.acm.org/doi/pdf/10.1145/3715014.3724047"
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
---