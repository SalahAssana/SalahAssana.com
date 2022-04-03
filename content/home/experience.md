---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

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
  - title: Research Assistant II
    company: Harvard Medical School
    company_url: 'https://hms.harvard.edu/'
    company_logo: hms
    location: Bostonm, MA
    date_start: '2021-01-01'
    date_end: ''
    description: |2-
        
        * Increased the speed of a free-breathing, free-running perfusion sequence by 1000\% using deep learning.
        * Deployed ML models on Siemens scanner for real-time data processing using FIRE framework.
        * Collaborated with MRI technicians to add-on experimental scans to clinical patients.
        
  - title: Research Assistant
    company: MIT Media Lab
    company_url: 'https://www.media.mit.edu/'
    company_logo: mit-ml
    location: Cambridge, MA
    date_start: '2018-09-01'
    date_end: '2020-05-31'
    description: |2-
        
        * Developed a novel mmWave sensor capable of contactless cardiovascular activity monitoring.
        * Used C++ Boost library to enable the use of multiple sensors concurrently and allow for real-time data evaluation.
        * Used MATLAB to filter signal and analyze the cardiac data for signs of heart illnesses.

  - title: Software Engineer
    company: Booz Allen Hamilton
    company_url: 'https://www.boozallen.com/'
    company_logo: bah
    location: Tysons, VA
    date_start: '2018-09-01'
    date_end: '2020-05-31'
    description: |2-
        
        * Worked as full stack developer on a scrum team with C\# and JavaScript libraries like AngularJS \& Backbone.
        * Used Hadoop and Hive to build a scalable distributed data lake on AWS.
        * Built a abstractive text summarization tool using TensorFlow, NumPy, Pandas and Pyrouge

  - title: Research Assistant
    company: UVA Link Lab
    company_url: 'https://engineering.virginia.edu/link-lab'
    company_logo: uva
    location: Charlottesville, VA
    date_start: '2015-09-01'
    date_end: '2017-05-31'
    description: |2-
        
        * Introduced a new doorway sensor capable of determine travel direction with 99.7\% accuracy.
        * Wrote multi-threaded C driver to increase speed of sensor by 3000\% \& reduced energy consumption by 50\%.
        * Develop optical flow based tracking algorithm robust to illumination changes \& background movement in Python.

design:
  columns: '2'
---
