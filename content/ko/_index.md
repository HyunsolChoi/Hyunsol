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
      banner:
        # Upload a cover image to `assets/media/` folder and reference its filename here (optional)
        filename: 'coding.jpg'
  - block: collection
    content:
      filters:
        folders:
          - blog
        kinds: 
          - page
      sort_by: 'Date'
      text: 'Recent Posts'
      filter_button:
        - name: All
          tag: '*'
        - name: API
          tag: API
        - name: WEB
          tag: WEB
    design:
      # Choose a listing view
      view: masonry
      spacing:
        padding: ['3rem', 0, '6rem', 0]
      # For the Showcase view, do you want to flip alternate rows?
      columns: '2'
      flip_alt_rows: false
    
     
---
