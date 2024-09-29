---
title: ""
hide_date: true
type: landing

sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      css_class: dark
      spacing:
       padding: [0, 0, 0, 0]
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
      banner:
        # Upload a cover image to `assets/media/` folder and reference its filename here (optional)
        filename: 'coding.jpg'
  - block: collection
    content:
      filters:
        folders:
          - blog
      sort_by: 'Date'
      text: 'Recent Posts'
    design:
      spacing:
        padding: ['3rem', 0, '6rem', 0]
      view: article-grid
      columns: 2
     
---
