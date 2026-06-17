---
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
      title: '📡 My research'
      subtitle: ''
      text: |-
        I focus on energy-efficient resource management in disaggregated 5G O-RAN
        systems. My main contribution, BRAVE-O, is a Multi-Agent Deep Reinforcement
        Learning framework that jointly optimizes PRB blanking and VNF placement to
        reduce the energy footprint of next-generation RAN deployments, validated on
        the SLICES-RI European testbed.

        Always happy to connect with fellow researchers working on O-RAN, network
        optimization, or reinforcement learning 😃
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & upcoming talks
      filters:
        folders:
          - events
    design:
      view: card
  - block: collection
    id: news
    content:
      title: Recent news
      subtitle: ''
      text: ''
      page_type: blog
      count: 10
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
