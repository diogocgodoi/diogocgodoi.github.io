---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: me
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true

  - block: logos
    content:
      title: Programming skills
      items:
        - name: R
          image: logos/R.png
          url: 
          description: R
        - name: Python
          image: logos/Python.png
          url: 
          description: Python
        - name: JavaScript
          image: logos/js.png
          url: 
          description: JavaScript
        - name: HTML
          image: logos/html.png
          url: 
          description: HTML
        - name: CSS
          image: logos/css.png
          url: 
          description: CSS
    design:
      layout: carousel
      #logo_style: original
      logo_size: lg
---
