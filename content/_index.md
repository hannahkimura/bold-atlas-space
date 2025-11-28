---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: 'Recent Projects'
      subtitle: ''
      text: |-
       - [tree-sitter-objectscript](https://github.com/hkimura-intersys/tree-sitter-objectscript). 
       - [objectscript-lsp](https://github.com/hkimura-intersys/objectscript-lsp). 
       - mondegreens: [git repo](https://github.com/mpoliak/studies_aux), [conference paper](https://escholarship.org/uc/item/3mf978x8). 
    design:
      columns: '1'
  