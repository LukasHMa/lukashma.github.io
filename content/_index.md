---
# Leave the homepage title empty to use the site title
# Check https://hugoblox.com/blocks/ for more blocks templates
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/vita_LM_Dec25.pdf
      # headings:
      #   about: ''
      #   education: ''
      #   interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: compact # Options: compact (long names), balanced (default), display (short names)

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  
  - block: markdown
    content:
      title: 'Research interests'
      subtitle: ''
      text: |
       - Nation-building
       - Identity formation
       - Peace and conflict
       - Migration
    design:
      columns: '1'

  # - block: collection
  #   id: papers
  #   content:
  #     title: Publications
  #     filters:
  #       folders:
  #         - publications
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2

  # - block: collection
  #  content:
  #    title: Recent Publications
  #    text: ''
  #    filters:
  #      folders:
  #        - publications
  #      exclude_featured: false
  #  design:
  #    view: citation

  - block: collection
    content:
      title: Working Papers
      filters:
        folders:
          - working_paper
    design:
      view: card

  - block: collection
    content:
      title: Work in Progress
      filters:
        folders:
          - projects
    design:
      view: card

  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: blog
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 10
  #     # Filter on criteria
  #     filters:
  #       author: ''
  #       category: ''
  #       tag: ''
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ''
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: card
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]

#   - block: cta-card
#     content:
#       title: 👉 Build your own academic website like this
#       text: |-

#       button:
#         text: Get Started
#         url: https://hugoblox.com/templates/
#     design:
#       card:
#         # Card background color (CSS class)
#         css_class: 'bg-primary-300 dark:bg-primary-700'
#         css_style: ''
---
