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

  - block: features
    content:
      title: ''
      subtitle: ''
      text: ''
      items:
        - name: 데이터베이스
          description: 데이터베이스는 데이터를 체계적으로 저장하고 관리하는 시스템으로, 여러 사용자와 응용 프로그램이 효율적으로 데이터를 생성, 조회, 수정 및 삭제할 수 있도록 돕습니다.
          icon: solid/database
          icon_pack: fab
        - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Photography
          description: 10%
          icon: camera-retro
          icon_pack: fas

  - block: markdown
    content:
      title: 연락처
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text="더보기 →" %}}
    design:
      columns: '1'
---
