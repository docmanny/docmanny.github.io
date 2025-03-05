---
date: "2022-10-24"
design:
  spacing: 6rem
sections:
- block: resume-biography-4
  content:
    button:
      text: Download CV
      url: https://github.com/docmanny/cv/raw/master/JuanVazquezCV.pdf
    buttons:
        - text: "\U0001F449 Join the Vazquez Lab! \U0001F448"
          url: https://lab.vazquez.bio/
    text: ""
    username: JMV
    
  design:
    background:
      color: black
      image:
        filename: openart-bats-landscape.png
        filters:
          brightness: 0.3
        parallax: false
        position: center
        size: cover
    css_class: dark

- block: markdown
  content:
    title: "The Genetics of Extraordinary Lifespan"
    subtitle: ""
    text: "Aging is one of the most ubiquitous and stunning rules of life, affecting all levels of biological organization across the tree of life. The incredible range of lifespans seen across vertebrates provides a rich source for the discovery of new pathways and drug targets for aging-associated diseases including ___cancer___, ___sarcopenia___, and ___dementia___. My work focuses on tackling interdisciplinary questions aging with equally interdisciplinary approaches, ranging from cellular and molecular biology to comparative evolutionary genomics and population genetics.\n\n
    I study the evolution of gene regulatory networks governing longevity-associated traits in extraordinarily long-lived animals to identify new therapeutic pathways for aging-related disease. This involves a combination of _in vitro_, _ex vivo_, and _in sillico_ approaches made possible by combining fieldwork, cellular and molecular biology, and functional genomics to enable studies that would be impossible _in vivo_. This system enables us to not only identify genes and regulatory pathways associated with the evolution of increased or decreased longevity; but also understand how the mechanisms behind these findings in a native context.\n\n
    I am always looking for collaborators, whether its to study a specific facet of aging in bats or whales, or to expand our horizons to new systems - just reach out!"
  design:
    columns: 1

- block: cta-card
  content:
    button:
      text: See the Vazquez Lab site
      url: https://lab.vazquez.bio/
    text: |-
      We're looking for grad students and postdocs at all levels!
    title: "\U0001F449 Wanna join the lab? \U0001F448"
  demo: false
  design:
    spacing:
        padding:
        - 0
        - 0
        - 0
        - 0
    card:
      css_class: bg-primary-800
      css_style: ""
    
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: 2
    view: article-grid
  id: papers
  
- block: collection
  content:
    filters:
      exclude_featured: false
      folders:
      - publication
    text: ""
    title: Recent Publications
  design:
    view: citation
    
- block: collection
  content:
    filters:
      folders:
      - event
    title: Recent & Upcoming Talks
  design:
    columns: 1
    view: article-grid
  id: talks
  
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: true
      exclude_past: false
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    page_type: post
    subtitle: ""
    text: ""
    title: Blog
  design:
    spacing:
      padding:
      - 0
      - 0
      - 0
      - 0
    view: date-title-summary
  id: blog
  
title: "Juan Manuel Vazquez"
type: landing
---
