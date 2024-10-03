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

  - block: contact
    content:
      title: Contact
      text: |-
        <br> <span style="font-size:95%">전북대학교 의료 AI 및 계산 수학 연구실 (Macs)의 학부연구생/석사 position에 관심 있으시면 아래로 연락주시면 감사드리겠습니다.</span> <br>
      email: ksl(at)jbnu.ac.kr
      phone: +82-63-270-2406
      address:
        street: 전북대학교 공과대학 7호관 626호
        city: 전주시
        region: 전라북도
        postcode: '54896'
        country: 대한민국
        country_code: KO
      coordinates:
        latitude: '35.84601324617979'
        longitude: '127.13444961966684'
      directions: 
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: true
    design:
      columns: '3'

---
