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
      spacing:
        padding: [0, 0, 0, 0]
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
      banner:
        # Upload a cover image to `assets/media/` folder and reference its filename here (optional)
        filename: coding.jpg
        
  - block: collection
    content:
      filters:
        folders:
          - blog
      sort_by: 'Date'
      text: 'Recent Posts'
      count: 0
    design:
      spacing:
        padding: ['3rem', 0, '6rem', 0]
      view: article-grid
      columns: 2

  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: Read my latest paper on LLMs
          icon: academicons/arxiv
          url: https://arxiv.org/abs/2304.01852
        - text: Watch my new YouTube video to achieve 20x productivity
          icon: brands/youtube
          url: https://youtube.com
        - text: Connect with me on LinkedIn
          icon: brands/linkedin
          url: https://linkedin.com

---
