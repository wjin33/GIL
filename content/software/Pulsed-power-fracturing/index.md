---
title: Electro-Hydraulic Fracturing
date: 2025-06-01

authors:
- Chunhui Zhao
- Wencheng Jin

summary: This software is built on the open-source parallel MOOSE framework and uses the finite-element method to model hydraulic fracturing. It solves momentum and mass conservation equations with advanced numerical techniques, enabling simulation of fracture propagation, proppant transport and settling, and fracture closure with compaction. The software also models pulsed-power-induced fracturing by solving coupled hydromechanical equations, incorporating damage models and evolving permeability and stiffness to capture multi-fracture growth in saturated environments.

# abstract:  

# links:
# - name: URL
#   url: https://doi.org/10.1016/j.powtec.2023.118625

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: C. Zhao & W. Jin'
  focal_point: Right

url_code: ''
url_pdf: 'https://onepetro.org/ARMAUSRMS/proceedings-abstract/ARMA25/ARMA25/D021S009R002/786136'
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
---
<!-- ![Hopper Flow](../../../images/hopper.gif) -->

The software has the following features:
- Hydraulic Fracturing with Proppant Transport
- Pulsed Power Fracturing with HM coupling (phase-field & Nonlocal gradient-based damage)