---
title: My page
hide_date: true
type: landing

sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      spacing:
       padding: [0, 0, 0, 0]
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
  - block: collection
    content:
      filters:
        folders:
          - blog
      sort_by: 'Date'
    design:
      # Choose a listing view
      view: card
      spacing:
        padding: ['3rem', 0, '6rem', 0]
     
---
