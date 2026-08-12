---
title: ""
summary: ""
date: "2022-10-24"
type: "landing"
sections:
  - block: "resume-biography-3"
    content:
      username: "me"
      text: ""
      button:
        text: "Download CV"
        url: "uploads/Academic_CV_Diogo_August_2026.pdf"
      headings:
        about: ""
        education: ""
        interests: ""
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: "md"
      avatar:
        size: "medium"
        shape: "circle"
    ce: "section-6aa1e00c"
    As: "section-86d93ecd"

  - block: "collection"
    content:
      sort_by: Title
      sort_ascending: true
      title: "Presentations & Conferences"
      filters:
        folders:
          - "events"
        featured_only: false
    design:
      view: "article-grid"
      columns: 3
    ce: "section-talks"
    id: "talks"
    As: "section-b7bd310e"


  - block: "collection"
    content:
      title: "Featured Publications"
      filters:
        folders:
          - "publications"
        featured_only: true
    design:
      view: "article-grid"
      columns: 3
    ce: "section-papers"
    id: "papers"
    As: "section-dad16b48"
    

#  - block: resume-experience
#    content:
#      username: me
 #   design:
  #    # Hugo date format
   #   date_format: 'January 2006'
    #  # Education or Experience section first?
     # is_education_first: true
   # ce: "section-experience"
    # id: "experience"



  - block: "collection"
    content:
      title: "All Publications"
      text: ""
      filters:
        folders:
          - "publications"
        exclude_featured: false
    design:
      view: "citation"
    ce: "section-9437a676"
    As: "section-ec1fe49c"


  - block: logos
    content:
      title: Current & Previous Institutional Affiliations
      items:
        - name: Cardiff
          image: logos/cardiff.png
          url: https://www.cardiff.ac.uk/
          description: Cardiff University
        - name: Cambridge 
          image: logos/cambridge.jpeg
          url: https://www.cam.ac.uk/
          description: Cambridge
        - name: UNSW
          image: logos/unsw.jpeg
          url: https://www.unsw.edu.au/
          description: University of New South Wales
    design:
      layout: row
      logo_style: grayscale
      logo_size: lg
---