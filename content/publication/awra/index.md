---
title: "Continental scale downscaling of AWRA-L analysed soil moisture using random forest regression"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Luigi J. Renzullo
- Siyuan Tian

# Author notes (optional)
author_notes:
- ""
- ""
- ""
- ""

date: "2021-12-17T00:00:00Z"
doi: "https://doi.org/10.36334/modsim.2021.J10.yu"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *24th International Congress on Modelling and Simulation, Sydney, Australia.*
publication_short: In *MODSIM2021*

abstract: The Australian Water Resource Assessment Landscape (AWRA-L) model as used by the Bureau of Meteorology (BoM) provides daily continental scale soil moisture (SM) estimates (among other landscape water variables) at ~5-km resolution. At such a coarse scale these data cannot represent the high spatiotemporal variability of SM across heterogeneous land surfaces. Downscaling of coarse SM products based on machine learning (ML) has become increasingly popular due to its robust predictions and potential for large-scale applications. As a first step towards high-resolution daily Australia-wide SM estimation, a downscaling framework was developed to generate monthly SM with 500-m spatial resolution using analysed SM from AWRA-L and multisource geospatial predictors in random forest (RF) regression. Candidate predictors include digital elevation model (DEM), soil properties from the Australian soil and landscape grids, and several retrievals from the MODerate-resolution Imaging Spectroradiometer (MODIS). Ten experiments were conducted to decide the best combination of predictors...

# Summary. An optional shortened abstract.
summary: The downscaled SM shows greatly enhanced spatial details at the local scale while maintaining consistent patterns with AWRA-L analysis at the continental scale. Validations against in-situ measurement networks using Pearson correlation coefficient (R) show that there is very little difference in the performance between the downscaled and AWRA-L SM.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.mssanz.org.au/modsim2021/papers/J10/yu.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
