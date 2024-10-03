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

  - block: slider  
    content:
     slides:
      - title: <span style="font-size:80%">데이터베이스</span>
        contnet: <span style="font-size:75%>데이터를 보다 체계적으로 관리할 수 있도록 구조화된 시스템
        align: center
        background:
          image:
            fillename: database.jpg
            filters:
              brightness: 0.7
          position: center

      - title: <span style="font-size:80%">알고리즘</span>
        contnet: <span style="font-size:75%>특정 문제를 해결하기 위한 명확하고 단계적인 절차
        align: center
        background:
          image:
            fillename: algorithm.jpg
            filters:
              brightness: 0.7
          position: center

      - title: <span style="font-size:80%">웹</span>
        contnet: <span style="font-size:75%>인터넷 기반 정보 연결망, 웹 페이지, 웹 애플리케이션을 통해 콘텐츠 및 서비스 제공
        align: center
        background:
          image:
            fillename: web.jpg
            filters:
              brightness: 0.7
          position: center
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 5000   

---
