---
title: "An inline deep learning based free-breathing ECG-free cine for exercise cardiovascular magnetic resonance"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Manuel Morales
- admin

# Author notes (optional)
author_notes: ""

date: "2022-08-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-08-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Journal of Cardiovascular Magnetic Resonance*
publication_short: In *JCMR*

abstract: Exercise cardiovascular magnetic resonance (Ex-CMR) is a promising stress imaging test for coronary artery disease (CAD). However, Ex-CMR requires accelerated imaging techniques that result in significant aliasing artifacts. Our goal was to develop and evaluate a free-breathing and electrocardiogram (ECG)-free real-time cine with deep learning (DL)-based radial acceleration for Ex-CMR. A 3D (2D + time) convolutional neural network was implemented to suppress artifacts from aliased radial cine images. The network was trained using synthetic real-time radial cine images simulated using breath-hold, ECG-gated segmented Cartesian k-space data acquired at 3 T from 503 patients at rest. A prototype real-time radial sequence with acceleration rate = 12 was used to collect images with inline DL reconstruction. Performance was evaluated in 8 healthy subjects in whom only rest images were collected.

# Summary. An optional shortened abstract.
summary: To develop and evaluate a free-breathing and electrocardiogram-free real-time cine with deep learning-based radial acceleration for Ex-CMR.

tags: [exercise-cmr, stress-imaging, cardiology, machine-learning, medical-imaging]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://jcmr-online.biomedcentral.com/articles/10.1186/s12968-022-00879-9'
url_code: 'https://github.com/HMS-CardiacMR/DRAPR'
url_dataset: 'https://dataverse.harvard.edu/dataverse/cardiacmr'
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
