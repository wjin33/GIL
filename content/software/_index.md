---
title: Software
date: 2026-07-27
type: landing

sections:
  - block: markdown
    id: software-overview
    content:
      title: Research Software
      subtitle: Computational tools that turn multiscale physics into predictive capability
      text: |
        GIL develops research software for coupled mechanics, flow, transport, fracture propagation, and accelerated simulation. Each project connects numerical methods to a specific energy or Earth-system challenge.

        {{% cta cta_link="../research/" cta_text="Explore the research" cta_alt_link="../contact/" cta_alt_text="Discuss collaboration" %}}
    design:
      columns: '1'
      css_class: gil-page-intro
      background:
        gradient_start: '#f6f1ed'
        gradient_end: '#ffffff'
        gradient_angle: 135
      spacing:
        padding: ['6rem', '0', '5rem', '0']

  - block: collection
    id: current-software
    content:
      title: Current Software
      subtitle: High-fidelity tools for fluid-driven and dynamic fracture
      text: ""
      count: 2
      filters:
        tag: Current Software
      archive:
        enable: false
    design:
      view: gil-showcase
      columns: '1'
      flip_alt_rows: true
      css_class: gil-portfolio gil-software-gallery
      spacing:
        padding: ['5rem', '0', '4rem', '0']

  - block: collection
    id: additional-software
    content:
      title: Prior & Supporting Software
      subtitle: Earlier open research tools retained for reference and reuse
      text: ""
      count: 1
      filters:
        tag: Supporting Software
      archive:
        enable: false
    design:
      view: compact
      columns: '2'
      css_class: gil-foundational
      background:
        color: '#f7f5f2'
      spacing:
        padding: ['4.5rem', '0', '4.5rem', '0']

  - block: markdown
    content:
      title: Build on GIL Research
      subtitle: Connect software, publications, and collaboration
      text: |
        Review the associated publications for model formulation and validation, or contact GIL to discuss research use and collaboration.

        {{% cta cta_link="../publication/" cta_text="Browse publications" cta_alt_link="../contact/" cta_alt_text="Contact GIL" %}}
    design:
      columns: '1'
      css_class: gil-portfolio-cta
      background:
        gradient_start: '#500000'
        gradient_end: '#2d0000'
        gradient_angle: 120
        text_color_light: true
      spacing:
        padding: ['4.5rem', '0', '4.5rem', '0']
---
