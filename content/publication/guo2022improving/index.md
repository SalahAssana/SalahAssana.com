---
title: "Improving accuracy of myocardial T1 estimation in MyoMapNet"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Rui Guo
- Zhensen Chen
- Amine Amyar
- Hossam El‐Rewaidy
- admin

# Author notes (optional)
author_notes: ""

date: "2022-08-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-08-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Magnetic Resonance in Medicine*
publication_short: In *MRM*

abstract: MyoMapNet is a fully connected neural network for T1 estimation of an accelerated cardiac T1 mapping sequence, which collects 4 T1‐weighted images by a single Look‐Locker inversion‐recovery experiment (LL4). MyoMapNet was originally trained using in vivo data from the modified Look‐Locker inversion recovery sequence, which resulted in significant bias and sensitivity to various confounders. This study sought to train MyoMapNet using signals generated from numerical simulations and phantom MR data under multiple simulated confounders. The trained model was then evaluated by phantom data scanned using new phantom vials that differed from those used for training.

# Summary. An optional shortened abstract.
summary: To improve the accuracy and robustness of T1 estimation by MyoMapNet, a deep learning–based approach using 4 inversion‐recovery T1‐weighted images for cardiac T1 mapping.

tags: [t1-maps, MOLLI, cardiology, machine-learning, medical-imaging]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://cardiacmr.hms.harvard.edu/files/cardiacmr/files/magnetic_resonance_in_med_-_2022_-_guo_-_improving_accuracy_of_myocardia.pdf'
url_code: 'https://github.com/HMS-CardiacMR/ImprovingMyoMapNetT1Estimation'
url_dataset: ''
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
