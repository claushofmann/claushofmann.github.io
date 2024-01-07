---
title: "Using Recurrent Neural Networks for Particle Tracking at the CERN Large Hadron Collider"
summary: "I created a Deep Learning-based approach for tracking matter particles in particle accelerators. My approach is based
on computer vision tracking techniques"
  
date: "2020-08-01T00:00:00Z"

image: 
caption:
focal_point: Smart

authors:
- admin

# Publication name and optional abbreviated publication name.
publication: Master's Thesis, University of Vienna
publication_short: Master's Thesis

publication_types: ["7"]

url_pdf: ''
url_code: https://github.com/claushofmann/trackml
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

featured: true

abstract: This thesis presents a novel, deep learning-based algorithm for particle tracking, which can be learned entirely from data. Particle tracking is a problem in high energy physics, where matter particles are accelerated in large particle accelerators, like the LHC at CERN, and then brought to collision within a particle detector. Upon these collisions, new particles are created, which are recorded by the detector at multiple locations. These recordings are called hits. A particle tracker fulfills the task of connecting all hits originating from a single particle to form the particle’s trajectory. The tracker presented in this thesis is based on an approach from computer vision, where objects, like persons, are tracked in a video sequence. The presented tracker can track smaller amounts of particles simultaneously using end-to-end learning, i.e., the task of particle tracking is learned only from data and without any explicitly implemented physical models. Possible reasons hindering the tracker from scaling to very large particle densities are explored, and possible solutions suggested.

pdf: thesis

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---
