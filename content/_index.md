---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-07-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
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
---