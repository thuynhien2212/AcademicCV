---
date: "2022-10-24"
design:
  spacing: 6rem
sections:
- block: resume-biography-3
  content:
    button:
      text: Download CV
      url: uploads/resume.pdf
    text: ""
    username: admin
  design:
    background:
      image:
        filename: newbg.jpg
        filters:
          brightness: 1
        parallax: false
        position: center
        size: cover
    css_class: dark
- block: markdown
  content:
    title: "Summary"
    text: "I hold a bachelor's degree in Pharmacy in 2021 and currently serve as a researcher in the Department of Pharmaceutical Administration at the University of Medicine and Pharmacy in Ho Chi Minh City, Vietnam. With five years of expertise in data analysis using STATA and R, alongside qualitative and quantitative analysis, my research interests include Health Economic Modelling, Health Technology Assessment, and the Antibiotic Stewardship Program (ASP), with a focus on evaluating healthcare interventions and optimizing resource allocation to improve public health outcomes. Eager to learn, share knowledge, and uphold a strong sense of responsibility, I am pursuing an academic career."
  design:
    columns: "1"
- block: features
  id: skills
  content:
    items:
      - icon: r-project
        icon_pack: custom
        name: R
        description: 90%
      - icon: cube
        icon_pack: fas
        name: Statistics
        description: 100%
      - icon: camera-retro
        icon_pack: fas
        name: Photography
        description: 10%
    title: Skills
  design:
    columns: 3
- block: resume-skills
  content:
    title: Languages
    text: ''
    # Choose a user to display skills from (a folder name within `content/authors/`)
    username: admin
  design:
    columns: '2'
- block: custom_experience
  id: experience
  content:
    title: Experience
    date_format: Jan 2006
    text: ''
    # Choose a user to display skills from (a folder name within `content/authors/`)
    username: admin
  design:
    columns: '1'
- block: markdown
  content:
    subtitle: ""
    text: "Use this area to speak to your mission. I'm a research scientist in the
      Moonshot team at DeepMind. I blog about machine learning, deep learning, and
      moonshots.\n\nI apply a range of qualitative and quantitative methods to comprehensively
      investigate the role of science and technology in the economy.\n\nPlease reach
      out to collaborate \U0001F603"
    title: "\U0001F4DA My Research"
  design:
    columns: "1"
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: 2
    view: compact
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
    view: showcase
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
      exclude_future: false
      exclude_past: false
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    page_type: post
    subtitle: ""
    text: ""
    title: Recent News
  design:
    spacing:
      padding:
      - 0
      - 0
      - 0
      - 0
    view: date-title-summary
  id: news
title: ""
type: landing
---
