---
date: "2022-10-24"
design:
  spacing: 6rem
sections:
- block: resume-biography-3
  content:
    button:
      text: Download CV
      url: resume.pdf
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
- block: features
  id: skills
  content:
    items:
      - icon: r-project
        icon_pack: custom
        name: Programming
        description: Highly adaptive learner
      - icon: cube
        icon_pack: fas
        name: Statistics and Math Modelling
        description: A stickler for detail
      - icon: keyboard
        icon_pack: fas
        name: Academic Writing
        description: Eager beginner
      - icon: comments
        icon_pack: fas
        name: Communication
        description: Proactive collaborator
      - icon: timeline
        icon_pack: fas
        name: Project Management
        description: Careful planner
      - icon: people-group
        icon_pack: fas
        name: Teamworking
        description: Reliable team member    
    title: Skills
  design:
    columns: 3
- block: resume-awards
  content:
    title: Certifications
    text: ''
    username: admin
  design:
    date_format: Jan 2006
# - block: resume-skills
#   content:
#     title: Languages
#     text: ''
#     username: admin
#   design:
#     columns: '2'
- block: custom_experience
  id: experience
  content:
    title: Experience & Education
    date_format: Jan 2006
    text: ''
    # Choose a user to display skills from (a folder name within `content/authors/`)
    username: admin
  design:
    columns: '1'
- block: collection
  id: publication
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: ""
    title: Publications
  design:
    view: citation
- block: collection
  id: conference
  content:
    filters:
      exclude_featured: true
      folders:
      - conference
    text: ""
    title: Conferences
  design:
    view: card
# - block: markdown
#   content:
#     subtitle: ""
#     text: "Use this area to speak to your mission. I'm a research scientist in the
#       Moonshot team at DeepMind. I blog about machine learning, deep learning, and
#       moonshots.\n\nI apply a range of qualitative and quantitative methods to comprehensively
#       investigate the role of science and technology in the economy.\n\nPlease reach
#       out to collaborate \U0001F603"
#     title: "\U0001F4DA My Research"
#   design:
#     columns: "1"
# - block: collection
#   content:
#     filters:
#       featured_only: true
#       folders:
#       - publication
#     title: Featured Publications
#   design:
#     columns: 2
#     view: compact
#   id: papers
# - block: collection
#   content:
#     filters:
#       exclude_featured: false
#       folders:
#       - publication
#     text: ""
#     title: Recent Publications
#   design:
#     view: showcase
# - block: collection
#   content:
#     filters:
#       folders:
#       - event
#     title: Recent & Upcoming Talks
#   design:
#     columns: 1
#     view: article-grid
#   id: talks
# - block: collection
#   content:
#     count: 5
#     filters:
#       author: ""
#       category: ""
#       exclude_featured: false
#       exclude_future: false
#       exclude_past: false
#       publication_type: ""
#       tag: ""
#     offset: 0
#     order: desc
#     page_type: post
#     subtitle: ""
#     text: ""
#     title: Recent News
#   design:
#     spacing:
#       padding:
#       - 0
#       - 0
#       - 0
#       - 0
#     view: date-title-summary
#   id: news
title: ""
type: landing
---
