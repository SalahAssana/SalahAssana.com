---
title: "Privacy-preserving image processing with binocular thermal cameras"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Erin Griffiths
- admin

# Author notes (optional)
author_notes: ""

date: "2018-01-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-01-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies*
publication_short: In *IMWUT*

abstract: Today, cameras and digital image processing are transforming industries and the human environment with rich, informative sensing. However, image processing is not utilized nearly as much in homes where concerns about image privacy dominate. In a preliminary study with 200 participants, we found 21% would reject a camera based system even if the system was designed to not report images as they could still be collected if the camera system was hacked. In this paper, we demonstrate a hardware-based approach for privacy-preserving image processing, the ability to automatically extract information from imaging sensors without the risk of compromising image privacy, even if the system is hacked. The basic idea is to limit both the memory available on board the camera and the data rate of camera communication to prevent a full image from ever being extracted. As a proof of concept, we prototype a system, called Lethe, that tracks and identifies individuals by height with a thermal camera as they move from room to room. Our results show that Lethe can detect the presence of individuals with 96.9% accuracy and determine their direction of travel with 99.7% accuracy. Additionally, Lethe can identify individuals 96.0% of the time with a 5cm (~2in) or greater difference in walking height and 92.9% with a 2.5cm (~1in) or greater difference. Finally, Lethe performs this processing with only 33 bytes of memory (or 0.69% of the full thermal image).

# Summary. An optional shortened abstract.
summary: Project Lethe | Privacy-Preserving Indoor Localization System

tags: [privacy, smart-home, sensors, thermal-camera, indoor-localisation]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3161198'
url_code: 'https://github.com/SalahAssana/Lethe'
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
