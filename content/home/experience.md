---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 70

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Assistant III
    company: Massachusetts General Hospital
    company_url: 'https://www.massgeneralbrigham.org/'
    company_logo: mgh
    location: Boston, MA
    date_start: '2024-04-01'
    date_end: ''
    description: |2-
    
        * Developing a reinforcement learning method, driven by an MRI physics simulator, to discover MR Fingerprinting sequences for ultra-low-field portable MRI. Hand-designed clinical schedules don't transfer to this regime.
        * Building a lung parenchyma segmentation model trained entirely on synthetic anatomical data. This sidesteps the ground-truth bottleneck, since parenchyma is hard to distinguish visually from pulmonary vasculature.
        * Developing a cardiac MRI segmentation model trained exclusively on synthetic images with randomized contrast and resolution. This makes it robust to the contrast variability across cardiac protocols.

  - title: Research Assistant II
    company: Beth Israel Deaconess Medical Center
    company_url: 'https://bidmc.org/'
    company_logo: bidmc
    location: Boston, MA
    date_start: '2021-01-01'
    date_end: '2024-03-31'
    description: |2-
    
        * Created MyoMapNet, a physics-informed network that cut cardiac T1 mapping from 17 heartbeats to 4, or 2 minutes to under 12 seconds. Validated in a multi-center study, deployed inline via Siemens OpenRecon, and open-sourced.
        * Built DRAPR, a 3D U-Net for 12x-accelerated real-time cardiac cine under stress. Enforcing data consistency against raw multi-coil k-space fixed a failure where image-domain training suppressed real motion.
        * Developed REGAIN, a resolution-enhancement GAN for cardiac cine. Training through the scanner's own parallel-imaging pipeline closed the simulation-to-real gap, enabling 13.6- to 16-fold effective acceleration.
        
  - title: Research Assistant
    company: MIT Media Lab
    company_url: 'https://www.media.mit.edu/'
    company_logo: mit-ml
    location: Cambridge, MA
    date_start: '2018-09-01'
    date_end: '2020-05-31'
    description: |2-
        
        * Invented a contactless mmWave sensor that records a seismocardiogram without a contact accelerometer. A differential filter separates periodic cardiac motion from aperiodic body motion.
        * Built a C++/Boost pipeline for real-time, concurrent multi-sensor acquisition. Used MATLAB to analyze the cardiac signal for markers of atrial fibrillation and ischemia.
        * Published as co-first author at ACM MobiCom 2020, a flagship mobile systems venue. The work became my master's thesis on contactless cardiovascular monitoring with mmWaves.

  - title: Machine Learning Engineer
    company: Booz Allen Hamilton
    company_url: 'https://www.boozallen.com/'
    company_logo: bah
    location: Tysons, VA
    date_start: '2017-09-01'
    date_end: '2018-08-31'
    description: |2-
        
        * Independently designed an abstractive text-summarization tool (bidirectional LSTM with attention) after finding that no existing tool met requirements. Built in TensorFlow, NumPy, and Pandas and evaluated with Pyrouge.
        * Architected a scalable, distributed data lake on AWS using Hadoop and Hive. It gave the team a foundation for storing and querying large datasets.
        * Served as a full-stack developer on a scrum team, building with C\# and JavaScript frameworks including AngularJS \& Backbone. Delivered features end to end within sprint cycles.

  - title: Research Assistant
    company: UVA Link Lab
    company_url: 'https://engineering.virginia.edu/link-lab'
    company_logo: uva
    location: Charlottesville, VA
    date_start: '2015-09-01'
    date_end: '2017-05-31'
    description: |2-
        
        * Designed a privacy-preserving doorway sensor using a binocular thermal camera, classifying direction of travel with 99.7\% accuracy. Images are processed on-device, so no identifiable data is transmitted.
        * Built a physics-grounded synthetic-data pipeline that renders thermal images from Planckian blackbody radiance and tissue emissivity. Standard augmentation failed to preserve the fidelity needed to generalize to real captures.
        * Rewrote the camera driver in branchless C and designed an optical flow algorithm using just 33 bytes of working memory on an 8-bit ATtiny. Throughput rose 3000\% while energy use fell 50\%.

design:
  columns: '2'
---