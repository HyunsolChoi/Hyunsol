---
title: About

type: landing

sections:
  - block: about.biography
    id: about
    content:
      title:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
    design:
      css_class: black
      background: 
        text_color_light: true
        image: # Add your image background to assets/media/.
          filename: bio-background.jpg
          filters:
            brightness: 0.8
          size: cover
          position: center 
          parallax: false
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="../skills/" cta_text="etc. →" %}}
    design:
      columns: '1'
---
