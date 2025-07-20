---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-05-20
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: jiboncom
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: CV
        url: uploads/Boncompte-resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    content:
      title: Job Market Paper
      text: ""
      filters:
        folders:
          - post
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: Work in Progress
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Software
      filters:
        folders:
          - project
    design:
      view: compact
      columns: 1
---
