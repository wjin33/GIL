---
# Leave the homepage title empty to use the site title
title:
date: 2025-09-14
type: landing

sections:
  - block: hero
    content:
      title: |
        Geosystem Innovation Laboratory
      image:
        filename: welcome.jpg
      text: |
        <br>
        The Geosystem Innovation Laboratory (GIL) in the Harold Vance Department of Petroleum Engineering at Texas A&M University focuses on: (1) innovative stimulation technologies for subsurface resource extraction, (2) physics-based and data-driven simulation of multiphysics processes in fractured porous media, and (3) granular material characterization and modeling.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
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
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}

        Explore our [research](./research/), browse our [software](./software/), or [contact us](./contact/) about collaboration opportunities.
    design:
      columns: '1'
---
