---
title: AI Acceleration of Physics-Based PDE Solvers
date: 2026-07-01
weight: 5
summary: Combine GPU computing, physics-constrained machine learning, learned corrections, and emulators to accelerate high-fidelity PDE solvers while preserving their governing physics.
authors:
  - Md Badrul Hasan
  - Wencheng Jin
tags:
  - Current Research
image:
  preview_filename: card.png
---

Many predictive models for energy and Earth systems solve coupled partial differential equations (PDEs) at high spatial and temporal resolution. These physics-based solvers provide interpretable, trustworthy predictions, but their computational cost can limit real-time forecasting, uncertainty quantification, inverse analysis, optimization, and decision support.

GIL develops **AI-accelerated scientific computing for physics-based PDE solvers** by combining:

- GPU acceleration of the governing numerical model,
- Physics-constrained machine learning for learned correction and interpolation,
- Data-driven emulators for rapid scenario and ensemble prediction, and
- Verification against the original high-fidelity solver to preserve physical consistency.

The goal is not to replace governing physics, but to make trusted simulation fast enough for time-critical and many-query applications.

<!--more-->

##### Flagship ONR YIP project: real-time coastal forecasting

Supported by an Office of Naval Research [Young Investigator Program](https://www.onr.navy.mil/2026-young-investigators) award and developed in collaboration with Deltares, the flagship project applies this framework to coastal hydro-morphodynamics during hurricanes and winter storms.

Large waves and storm surge can reshape the coast within hours: sand bars migrate, dunes erode, and low-lying areas flood. Process-based models such as [XBeach](https://oss.deltares.nl/web/xbeach/), developed by Deltares, resolve coupled wave, flow, sediment-transport, and bed-change processes, but a single high-resolution storm simulation can take hours to days on a CPU. Forecasting requires many such runs for ensembles and scenarios well before landfall.

GIL combines physics-based simulation on graphics processing units (GPUs) with physics-constrained machine learning so that storm-impact forecasts can run in near real time while retaining the physics of the original model. [Read the ONR Young Investigator Award announcement](../../post/26-2-19-YIP/).

##### GPU-accelerated physics-based simulation

Each XBeach time step performs the same local calculation in every grid cell, which suits GPUs. We port Deltares' Fortran source to GPUs with OpenACC directives, in double precision, so that the physics stays the same and the code remains reviewable by the XBeach developers. Waves, currents, sediment transport, and bed change with avalanching now run on the GPU, and every stage of the port is checked against the original CPU code on several GPU generations.

On a real sandy coast (Egmond, the Netherlands, about 200,000 grid cells, one hour of storm with sediment transport and bed change), one A100 GPU completes the run in under 4 minutes, compared with about 2 hours 46 minutes on one CPU core.

##### Physics-constrained machine learning

Running XBeach on a coarser grid is much cheaper, but it loses part of the wave and flow detail that drives sediment transport. We train neural networks on pairs of fine- and coarse-grid storm simulations to learn what the coarse grid misses, with physical constraints built into the models, and feed the learned correction back into the coarse simulation. The integrated workflow is:

**Storm forcing → GPU-accelerated coarse simulation → physics-constrained neural network → corrected forecast**

##### Emulators for morphodynamics

A third thrust develops data-driven emulators, trained on large sets of physics-based simulations, that predict bed evolution and other storm outcomes directly, to support rapid scenario analysis and uncertainty quantification.

##### Target outcomes

The project targets forecasts about 100 times faster than a standard CPU simulation, within 5% of its accuracy. Target capabilities include:

- Near real-time forecasts of waves, water levels, and flooding,
- Beach and dune erosion during extreme events,
- Rapid scenario analysis for coastal planning and operations, and
- Ensemble forecasts for uncertainty quantification.

Read more in the Texas A&M Engineering news story "[New model seeks to predict coastal changes in real time](https://news.engineering.tamu.edu/news/2026/04/08/new-model-seeks-to-predict-costal-changes-in-real-time/)."

##### Related presentations

1. Hasan, M. B., & Jin, W. (2026). Physics-Constrained Learned Closure of the Directional Wave-Action Equation for Accelerated Coastal Forecasting. AGU Fall Meeting 2026, San Francisco, CA, Session NG31A (poster).
