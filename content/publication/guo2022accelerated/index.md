---
title: "Accelerated cardiac T1 mapping in four heartbeats with inline MyoMapNet: a deep learning-based T1 estimation approach"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Rui Guo
- Hossam El-Rewaidy
- admin

# Author notes (optional)
author_notes: ""

date: "2022-01-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Journal of Cardiovascular Magnetic Resonance*
publication_short: In *JCMR*

abstract: Cardiovascular magnetic resonance (CMR) myocardial T1 and extracellular volume (ECV) mapping enable non-invasive quantification of diffuse interstitial fibrosis. Generally, myocardial T1 mapping consists of a preparation pulse and collection of a series of images to sample the recovering longitudinal magnetization at different time points. Based on the evolution of the longitudinal magnetization across the acquired T1-weighted images, T1 at each pixel could be determined. Over the past decade, there have been significant advances in myocardial T1 mapping sequence with different choices of magnetization preparation, number of collected T1-weighted images, and recovery period between different imaging blocks. Trade-offs depend on accuracy and precision. There are also differences in terms of coverage and respiratory motion compensation (free breathing vs. breath-holding). There is also growing interest in using a single sequence to simultaneously measure different tissue relaxation times. These approaches often require a more complicated fitting model with more parameters, resulting in a loss of precision and significantly longer reconstruction time, which reduce their clinical utility.

# Summary. An optional shortened abstract.
summary: To develop and evaluate MyoMapNet, a rapid myocardial T1 mapping approach that uses fully connected neural networks (FCNN) to estimate T1 values from four T1-weighted images collected after a single inversion pulse in four heartbeats (Look-Locker, LL4).

tags: [t1-maps, MOLLI, cardiology, machine-learning, medical-imaging]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://jcmr-online.biomedcentral.com/track/pdf/10.1186/s12968-021-00834-0.pdf'
url_code: 'https://github.com/HMS-CardiacMR/MyoMapNet'
url_dataset: 'https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/5MZYAH'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
