---
# Leave the homepage title empty to use the site title
title:

type: landing

sections:
  - block: slider
    content:
      slides:
        - title: <span style="font-size:80%; font-weight:600; color:#00B2B2;">저의 포트폴리오에 방문해주셔서 감사합니다</span>
          content: <span style="color:#00BFBF; font-weight:600;">해당 웹은 저를 소개하는 것을 목적으로 만들어졌습니다.</span>
          align: center
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: thank_you.jpg
              filters:
                brightness: 0.5
            position: right
            color: '#666'
        - title: <span style="font-size:80%; font-weight:600; color:#EAB8E4;">관심 분야에 대한 정보</span>
          content: <span style="color:#F4D3ED; font-weight:600;">전공 및 관심 분야에 대한 정보도 간략하게 다룹니다.</span>
          align: 
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: coding.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#555'
        - title: <span style="font-size:80%; font-weight:600; color:#FFB76B;">피드백 및 문의</span>
          content: <span style="color:#FFD6A0; font-weight:600;">피드백 및 문의, 컨택은 언제든 환영합니다</span>
          align: right
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: contact.jpg
              filters:
                brightness: 0.5
            position: center
            color: '#333'
          link:
            text: Contact
            icon: paper-plane
            icon_pack: fas
            url: contact
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      # Make the slides full screen within the browser window?
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 5000

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
          포트폴리오에 오신걸 환영합니다! </span><br>
        </div>
    design:
      spacing:
        padding: [0, 0, 0, 0]
 
  - block: collection
    content:
      title: <strong>최근 포스트</strong><br><br>
      subtitle: 
      text: 
      count: 4
      filters:
        folders:
          - post
      offset: 0
      order: desc
      page_type: post
    design:
      spacing:
         padding: ['5vh', '15vh', '7vh', '15vh']
      view: compact
      columns: 1
    archive:
      enable: true
      text: See all blog posts
      link: post/

  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text="Contact →" %}}
    design:
      columns: '1'
---
