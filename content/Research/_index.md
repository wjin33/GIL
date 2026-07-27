---
title: Research
date: 2026-07-27
type: landing

sections:
  - block: markdown
    id: research-overview
    content:
      title: Research
      subtitle: Multiscale mechanics, transport, and scientific AI for energy and Earth systems
      text: |
        GIL combines experiments, high-fidelity simulation, and machine learning to understand coupled processes from pores and fractures to reservoirs and engineered Earth systems.

        {{% cta cta_link="../tour/" cta_text="View the Research Tour" cta_alt_link="../publication/" cta_alt_text="Browse publications" %}}
    design:
      columns: '1'
      css_class: gil-page-intro
      background:
        gradient_start: '#f6f1ed'
        gradient_end: '#ffffff'
        gradient_angle: 135
      spacing:
        padding: ['6rem', '0', '5rem', '0']

  - block: features
    id: research-approach
    content:
      title: How We Approach Complex Systems
      subtitle: Connecting physics, computation, and data across scales
      text: |
        Our research framework links fundamental mechanisms to predictive tools for subsurface energy and engineered Earth systems.
      items:
        - name: Multiscale Mechanics
          icon: layer-group
          icon_pack: fas
          description: Connect microcrack initiation and fracture evolution to reservoir- and system-scale mechanical response.
        - name: Coupled Transport
          icon: water
          icon_pack: fas
          description: Resolve interacting deformation, fluid flow, heat transfer, and transport in porous and fractured media.
        - name: Scientific AI
          icon: brain
          icon_pack: fas
          description: Integrate physics-based simulation and machine learning for efficient prediction, optimization, and risk assessment.
    design:
      css_class: gil-research-lens
      background:
        color: '#f7f5f2'
      spacing:
        padding: ['5rem', '0', '5rem', '0']

  - block: collection
    id: current-research
    content:
      title: Current Research
      subtitle: Four connected priorities shaping GIL's present program
      text: ""
      count: 4
      sort_by: Weight
      sort_ascending: true
      filters:
        tag: Current Research
      archive:
        enable: false
    design:
      view: gil-showcase
      columns: '1'
      flip_alt_rows: true
      css_class: gil-portfolio gil-current-research
      spacing:
        padding: ['5rem', '0', '4rem', '0']

  - block: collection
    id: foundational-research
    content:
      title: Prior & Foundational Work
      subtitle: Earlier programs that continue to inform our methods and publications
      text: |
        These completed and foundational research themes remain available as part of GIL's scholarly record.
      count: 2
      filters:
        tag: Foundational Research
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
      title: Explore the Evidence
      subtitle: Publications, software, and opportunities to collaborate
      text: |
        Follow the research into peer-reviewed publications and reusable computational tools, or contact GIL to discuss collaboration.

        {{% cta cta_link="../publication/" cta_text="Browse publications" cta_alt_link="../software/" cta_alt_text="Explore software" %}}
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
