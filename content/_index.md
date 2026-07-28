---
# Leave the homepage title empty to use the site title
title:
date: 2025-09-14
type: landing

sections:
  - block: hero
    id: welcome
    content:
      title: |
        Geosystem Innovation Laboratory
      image:
        filename: welcome2.png
      text: |
        **Multiscale Mechanics, Transport, and Scientific AI for Energy and Earth Systems**

        GIL integrates experiments, high-fidelity simulation, and machine learning to understand and predict coupled processes from pores and fractures to reservoirs and engineered Earth systems.
      cta:
        label: Explore Our Research
        url: ./research/
        icon_pack: fas
        icon: arrow-right
      cta_alt:
        label: Meet the Team
        url: ./people/
      cta_note:
        label: Harold Vance Department of Petroleum Engineering · Texas A&M University
    design:
      css_class: gil-hero
      background:
        gradient_start: '#f6f1ed'
        gradient_end: '#ffffff'
        gradient_angle: 135
      spacing:
        padding: ['6rem', '0', '5rem', '0']

  - block: markdown
    id: research-tour-intro
    content:
      title: Research in Motion
      subtitle: A visual tour of current GIL investigations
      text: |
        Explore simulation results spanning dynamic fracture, coupled flow, induced seismicity, and subsurface thermal energy storage.

        [View the full Research Tour →](./tour/)
    design:
      columns: '1'
      css_class: gil-tour-intro
      background:
        color: '#f7f5f2'
      spacing:
        padding: ['4.5rem', '0', '1.75rem', '0']

  - block: slider
    id: research-tour
    content:
      slides:
        - title: Pulsed-Power Fracturing
          content: High-fidelity poro-dynamic simulations reveal how rapid energy release generates complex fracture networks in dry and saturated rock.
          align: left
          background:
            image:
              filename: pulsed_fracture.png
              position: center
              filters:
                brightness: 0.42
            color: '#20242a'
          link:
            icon: arrow-right
            icon_pack: fas
            text: Explore this research
            url: ./research/dynamic-fracturing/
        - title: Induced Seismicity
          content: Coupled models investigate why significant seismic events can occur after subsurface fluid injection has stopped.
          align: right
          background:
            image:
              filename: induced_seismicity.png
              position: center
              filters:
                brightness: 0.42
            color: '#20242a'
          link:
            icon: arrow-right
            icon_pack: fas
            text: Explore this research
            url: ./research/induced-seismicity/
        - title: Hydraulic Fracturing
          content: Multiscale computation captures the transition from distributed damage to fracture growth, transport, closure, and residual aperture.
          align: left
          background:
            image:
              filename: Hydraulic_Fracking.png
              position: center
              filters:
                brightness: 0.4
            color: '#20242a'
          link:
            icon: arrow-right
            icon_pack: fas
            text: Explore this research
            url: ./research/hydraulic-fracturing/
        - title: Hydraulic Fracture Swarm
          content: Develop a Lattice Beam based solver capable of modeling Mode-II and Mode-III fracture propagation.
          align: right
          background:
            image:
              filename: LatticeBeam.png
              position: center
              filters:
                brightness: 0.5
            color: '#20242a'
          link:
            icon: arrow-right
            icon_pack: fas
            text: Explore this research
            url: ./research/hydraulic-fracturing/
        - title: Multiphase Flow in Pores
          content: Quantify the impact of deformation on multiphase flow for porous media.
          align: left
          background:
            image:
              filename: LBMP.png
              position: center
              filters:
                brightness: 0.45
            color: '#20242a'
          link:
            icon: arrow-right
            icon_pack: fas
            text: Explore this research
            url: ./research/
        - title: Geothermal Energy Storage
          content: Integrated physics and machine learning help quantify storage performance and manage risk in subsurface thermal energy systems.
          align: right
          background:
            image:
              filename: RTES.png
              position: center
              filters:
                brightness: 0.42
            color: '#20242a'
          link:
            icon: arrow-right
            icon_pack: fas
            text: Explore this research
            url: ./research/rtes/
    design:
      css_class: gil-research-tour
      slide_height: '510px'
      is_fullscreen: false
      loop: true
      interval: 6500
      background:
        color: '#f7f5f2'
      spacing:
        padding: ['0', '0', '5rem', '0']

  - block: collection
    content:
      title: Latest News
      subtitle: Awards, presentations, workshops, and laboratory updates
      text: ""
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
      css_class: gil-news
      spacing:
        padding: ['4.5rem', '0', '4.5rem', '0']

  - block: collection
    content:
      title: Latest Publications
      subtitle: Recent contributions from GIL researchers and collaborators
      text: ""
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'
      css_class: gil-publications
      background:
        color: '#f7f5f2'
      spacing:
        padding: ['4.5rem', '0', '4.5rem', '0']

  - block: markdown
    content:
      title: Work With GIL
      subtitle: Research, collaboration, and student opportunities
      text: |
        We welcome students, researchers, and collaborators who want to advance sustainable subsurface energy, multiscale geomechanics, and scientific AI.

        {{% cta cta_link="./contact/" cta_text="Join GIL" cta_alt_link="./people/" cta_alt_text="Meet the team" %}}
    design:
      columns: '1'
      css_class: gil-cta
      background:
        gradient_start: '#500000'
        gradient_end: '#2d0000'
        gradient_angle: 120
        text_color_light: true
      spacing:
        padding: ['4.5rem', '0', '4.5rem', '0']
---
