---
title: Hydraulic Fracturing
date: 2019-12-15

authors:
- Wencheng Jin

summary: This MATLAB package simulates fluid-driven fracture propagation in porous, anisotropic materials across multiple scales. It combines a meso-scale nonlocal damage model, a macro-scale cohesive zone model, and a transition algorithm to capture multiscale mechanical behavior. Fluid flow in both the matrix and fractures is modeled using Darcy’s and Cubic laws, and XFEM is employed for discretization and solution of the boundary value problems.

# abstract: This software built on the open-source, parallel (Multiphysics Object-Oriented Simulation Environment) framework, using the finite-element method. It solves the momentum balance and mass conservation equations for hydraulic fracturing using numerical techniques such as the discontinuous Galerkin method, cohesive zone models, and multiphase, multicomponent fluid-flow simulations. This allows the software to simulate proppant-fluid mixture-driven fracture propagation, proppant transport and settling, and fracture closure with proppant compaction. ELK solves the coupled dynamic hydromechanical governing equations for electric shocking (i.e., pulsed-power-induced fracturing). A damage model and permeability and stiffness evolution constitutive laws have been incorporated to simulate multi-fracture propagation in saturated environments. 

# links:
# - name: URL
#   url: https://doi.org/10.1016/j.powtec.2023.118625

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: W. Jin'
  focal_point: Right

url_code: 'https://github.com/wjin33/Hydraulic-Fracturing'
url_pdf: 'https://link.springer.com/article/10.1007/s11440-019-00813-x'
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
- Energy based arc length control for mechanical solver
- Fully coupled fluid flow within matrix and along fracture with mechanical deformation
- Multiscale fracture propagation by coupling nonlocal damage with PPR cohesive zone model