---
title: "Poster: Drive-by City Wide Trash Sensing for Neighborhood Sanitation Need"

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`),
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
    - Tomas Fernandez
    - Yen Cheng Chang
    - Jesse Codling
    - Yiwen Dong
    - Jiale Zhang
    - Carlee Joe-Wong
    - Hae Young Noh
    - Pei Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: "2024-06-01"

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: "2025-09-11T01:11:27.568185Z"

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
    - paper-conference

# Publication name and optional abbreviated publication name.
publication:
    "*Proceedings of the 22nd Annual International Conference on Mobile Systems,
    Applications and Services*"
publication_short: "MOBISYS '24"

doi: 10.1145/3643832.3661431

abstract:
    Computer vision has been used more ubiquitously in recent years to understand
    and measure the environment around us, particularly in our neighborhoods. However,
    many city-wide sensing applications using vision require large labeling efforts,
    making various applications difficult on a wide scale. We propose a framework for
    labeling and self-training of in-car video to detect trash on the roads. Our approach
    requires minimal manual labeling to identify items not meant to be in the street,
    sidewalk, or public places, from a front-viewing car camera. Our system provides
    each frame of a video with a score indicating the amount of trash. To prevent overfitting,
    due to minimal available data, we remove data with high certainty of trash from
    the training dataset. The results show that our prediction with manually labeled
    ground truth yield an R2 of 0.66.

# Summary. An optional shortened abstract.
summary: ""

tags:
    - Julia
    - Poster/demo

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: "https://dl.acm.org/doi/pdf/10.1145/3643832.3661431"
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
projects: []
---

