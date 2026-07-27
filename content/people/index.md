---
title: People
date: 2026-07-27
type: landing

sections:
  - block: markdown
    id: people-overview
    content:
      title: People
      subtitle: One collaborative team connecting mechanics, transport, experiments, computation, and scientific AI
      text: |
        GIL brings together researchers with complementary perspectives and a shared commitment to understanding complex energy and Earth systems.
    design:
      columns: '1'
      css_class: gil-page-intro
      background:
        gradient_start: '#f6f1ed'
        gradient_end: '#ffffff'
        gradient_angle: 135
      spacing:
        padding: ['6rem', '0', '5rem', '0']

  - block: people
    id: team
    content:
      title: Meet GIL
      subtitle: Explore each profile to learn about individual research, experience, and interests
      user_groups:
        - GIL Team
      # Flat display order:
      # PI 10; postdocs 20-29; Ph.D. students 30-39;
      # master's students 40-49; undergraduate students 50-59.
      # Assign alphabetical values within each range.
      sort_by: people_order
      sort_ascending: true
    design:
      show_interests: false
      show_organizations: false
      show_role: true
      show_social: true
      css_class: gil-people
      background:
        color: '#f7f5f2'
      spacing:
        padding: ['5rem', '0', '5rem', '0']

  - block: markdown
    content:
      title: Work With GIL
      subtitle: Student, research, and collaboration opportunities
      text: |
        We welcome people who want to contribute to rigorous, creative research for energy and Earth systems.

        {{% cta cta_link="../contact/" cta_text="Join GIL" cta_alt_link="../research/" cta_alt_text="Explore our research" %}}
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
