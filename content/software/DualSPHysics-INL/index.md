---
title: DualSPHysics-INL

authors:
- Yumeng Zhao
- Wencheng Jin

summary: DualSPHysics-INL is an extended adaptation of the DualSPHysics open-source Smoothed Particle Hydrodynamics (SPH) simulation software based on DualSPHysics release version 5.0.1. Source code was modified from src_mphase/DSPH_v5.0_NNewtonian.  While DualSPHysics was developed for the simulation of fluid flow, DualSPHysics-INL was developed to simulate the flow of granular materials, such as soils and biomass feedstocks. In DualSPHysics-INL, a critical state soil mechanics based G-B hypoplastic constitutive model (Gudehus & Bauer) was adopted that has the capability to simulate granular materials of a wide range of mechanical responses. The code adopts a momentum-based boundary condition that is able to sustain impact loading without particles leaking to the outside of the boundaries and can achieve a full range of frictional conditions, including free-slip and no-slip. The code adopts GPU-acceleration, enabling fast computation for complex problems. The following examples provide a glance of applications that the DualSPHysics-INL can simulate!

abstract: DualSPHysics-INL is an extended adaptation of the DualSPHysics open-source Smoothed Particle Hydrodynamics (SPH) simulation software based on DualSPHysics release version 5.0.1. Source code was modified from src_mphase/DSPH_v5.0_NNewtonian.  While DualSPHysics was developed for the simulation of fluid flow, DualSPHysics-INL was developed to simulate the flow of granular materials, such as soils and biomass feedstocks. In DualSPHysics-INL, a critical state soil mechanics based G-B hypoplastic constitutive model (Gudehus & Bauer) was adopted that has the capability to simulate granular materials of a wide range of mechanical responses. The code adopts a momentum-based boundary condition that is able to sustain impact loading without particles leaking to the outside of the boundaries and can achieve a full range of frictional conditions, including free-slip and no-slip. The code adopts GPU-acceleration, enabling fast computation for complex problems. The following examples provide a glance of applications that the DualSPHysics-INL can simulate!

# links:
# - name: URL
#   url: https://doi.org/10.1016/j.powtec.2023.118625

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: Y. Zhao & W. Jin'
  focal_point: Right

url_code: 'https://github.com/IdahoLabResearch/DualSPHysics-INL.git'
url_pdf: 'https://doi.org/10.1016/j.powtec.2023.118625'
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

Features:
- Hypoplastic model
- Particle-particle interpolation-based non-slip boundary condition
- Particle-surface frictional boundary condition
- GPU accelerated simulation