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
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: me

  - block: resume-awards
    content:
      title: Awards
      username: me

  - block: resume-languages
    content:
      title: Languages
      username: me

  - block: logos
    content:
      title: Current & Previous Institutional Affiliations
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
      layout: row
      logo_style: grayscale
      logo_size: lg
---
