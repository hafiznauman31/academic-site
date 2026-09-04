---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: '🔬 Research Focus'
      subtitle: ''
      text: |-
        My research centers on fish environmental and thermal stress physiology, sustainable recirculating aquaculture systems (RAS), and oxidative stress mitigation. I investigate nutritional prophylactic interventions—specifically dietary antioxidants like ascorbic acid—and explore aquatic animal disease resilience, broodstock genetics, and tissue histopathology to enhance sustainable fish production.
    design:
      columns: '1'

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card

  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      page_type: blog
      count: 10
      filters:
        folders:
          - blog
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
