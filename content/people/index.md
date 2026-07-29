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

        {{% cta cta_link="#team" cta_text="Meet the team" cta_alt_link="#join" cta_alt_text="Join GIL" %}}
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
    id: openings
    content:
      title: Current Opening
      subtitle: Funded Ph.D. opportunity
      text: |
        **One Ph.D. position is available for Spring or Fall 2027.**

        Due to restrictions imposed by the funding agencies, the position is open only to U.S. citizens or [nonsensitive country nationals](https://www.energy.gov/sites/prod/files/2017/02/f34/Part%20VII%2C%20SECTION%20J%20-%20List%20of%20Documents%2C%20Exhibits%2Cand%20Other%20Attachments%20%20Attachment%20G_0.pdf). Applications will be accepted until the position is filled. Please [contact the PI](mailto:wencheng.jin@tamu.edu) for details.
    design:
      columns: '1'
      css_class: gil-openings
      background:
        color: '#ffffff'
      spacing:
        padding: ['3.5rem', '0', '3.5rem', '0']

  - block: contact
    id: join
    content:
      title: Join GIL
      text: |
        GIL welcomes graduate students, undergraduate researchers, postdoctoral researchers, visiting scholars, and collaborators who want to contribute to rigorous, creative research for energy and Earth systems.

        Our work spans sustainable energy, subsurface resource recovery, geomechanics, multiphysics modeling, transport in porous media, experimental mechanics, and scientific AI.

        Prospective researchers should email Dr. Wencheng Jin with a CV or résumé and a short description of their background, research interests, and goals. Graduate applicants should also review the [Texas A&M graduate admissions process](https://www.tamu.edu/admissions/how-to-apply/apply-as-graduate.html) and the [Harold Vance Department of Petroleum Engineering graduate admissions information](https://engineering.tamu.edu/petroleum/admissions-and-aid/graduate-admissions/index.html).

      email: wencheng.jin@tamu.edu
      phone: 979-458-7672
      address:
        street: 245 Spence St
        city: College Station
        region: TX
        postcode: '77843'
        country: United States
        country_code: US
      coordinates:
        latitude: '30.6194035908471'
        longitude: '-96.3389786850971'
      autolink: true
    design:
      columns: '1'
      css_class: gil-join
      background:
        gradient_start: '#f6f1ed'
        gradient_end: '#ffffff'
        gradient_angle: 135
      spacing:
        padding: ['5rem', '0', '5rem', '0']
---
