---
# Leave the homepage title empty to use the site title
title:

type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your profile text from `authors/admin/_index.md`?
      text: |
        <div>
        <span style="text-align: center"><br>
          안녕하세요! 전북대학교에서 컴퓨터공학을 전공하고 있는 최현솔입니다.</span><br>
        <span style="font-size:130%; font-weight: bold; text-align: center">
          저의 포트폴리오에 오신걸 환영합니다! </span><br>
        </div>
    design:
      spacing:
        padding: [0, 0, 0, 0]
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
      banner:
        # Upload a cover image to `assets/media/` folder and reference its filename here (optional)
        filename: coding.jpg
        caption: 'Image credit: [**Unsplash**](https://unsplash.com/)'

  - block: collection
    content:
      title: <strong>Latest Posts</strong>
      subtitle: 
      text: 
      count: 5
      filters:
        folders:
          - post
      offset: 0
      order: desc
      page_type: post
    design:
      spacing:
         padding: ['1rem', '15rem', '2rem', '15rem']
      view: compact
      columns: 1
    archive:
      enable: true
      text: See all blog posts
      link: post/
    
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
