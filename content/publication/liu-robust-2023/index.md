---
title: A robust interface finite element formulation for modeling brittle material
  failure problems
authors:
- Ruijie Liu
- Wencheng Jin
- Logan Harbour
- Fande Kong
- Cody Permann
- Derek Gaston
- Robert Podgorney
date: '2023-01-01'
publishDate: '2025-09-13T17:29:45.990858Z'
publication_types:
- article-journal
publication: '*International Journal for Numerical Methods in Engineering*'
doi: 10.1002/nme.7298
abstract: Failure of many brittle materials and structures can be modeled using interface-oriented
  finite elements combined with intrinsic cohesive zone models. The discontinuous
  Galerkin (DG) finite element method provides an innovative framework for modeling
  brittle crack propagation with zero-thickness interface elements, which can accommodate
  extrinsic cohesive laws to avoid the artificial compliance required in intrinsic
  cohesive models. However, robust formulations and implementations of DG methods
  are critical in alleviating the well-known convergence issues for both crack nucleation
  and propagation with reduced instability. This paper presents a robust interface
  element formulation by modifying the incomplete interior penalty Galerkin (IIPG)
  method, which successfully avoids the initial element interface penetration across
  elements that occurs prior to crack nucleation, and thereby greatly reduces the
  instability issue as cracks open. We further verified and validated our implementation
  by using a bar tension test and a beam fracturing benchmark. The robustness of our
  proposed interface element method was demonstrated by a micromechanics fiber/matrix
  debonding problem with 64 fibers embedded in a bulk matrix.
tags:
- fracture
- DG
- FRC
- IIPG
- intrinsic/extrinsic cohesive law
links:
- name: URL
  url: https://onlinelibrary.wiley.com/doi/abs/10.1002/nme.7298
---
