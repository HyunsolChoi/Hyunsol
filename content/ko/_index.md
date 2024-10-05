---
# Leave the homepage title empty to use the site title
title:

type: landing

sections:
  - block: slider
    content:
      slides:
        - title: | 
            <span style="font-size:80%; font-weight:600;">안녕하세요. 대학생 개발자 최현솔입니다</span>
          content: <span style="font-weight:600;">저의 포트폴리오에 방문해주셔서 감사합니다!</span>
          align: center
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: laptop.jpg
              filters:
                brightness: 0.5
            position: right
            color: '#666'
        - title: <span style="font-size:80%; font-weight:600;">소개</span>
          content: <span style="font-weight:600;">저에 대해 간략히 소개하고자 합니다</span>
          align: right
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: coding.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#555'
          link:
            text: Profile
            icon: user
            icon_pack: fas
            url: about/
        - title: <span style="font-size:80%; font-weight:600;">관심 분야</span>
          content: <span style="font-weight:600;">저의 관심 분야들을 소개합니다</span>
          align: right
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: interest-main.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#555'
          link:
            text: Interest
            icon: star
            icon_pack: fas
            url: interest/
        - title: <span style="font-size:80%; font-weight:600;">프로젝트</span>
          content: <span style="font-weight:600;">각종 경험/프로젝트들을 포스팅했습니다</span>
          align: right
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: posts.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#555'
          link:
            text: Post
            icon: newspaper
            icon_pack: fas
            url: post/
        - title: <span style="font-size:80%; font-weight:600;">피드백 및 문의</span>
          content: <span style="font-weight:600;">피드백 및 문의, 컨택은 언제든 환영합니다</span>
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
        <span style="font-size:100%; font-weight: bold; text-align: center">
          전북대학교에서 컴퓨터공학을 전공하고 있는 최현솔입니다.<br>
          유능한 백엔드 개발자가 되기위해 공부 중입니다. 
        </span>
        </div>
    design:
      spacing:
        padding: [0, 0, 0, 0]
 
  - block: features
    content:
      title: <span style="font-weight:bold">현재 관심 분야</span>
      subtitle: 
      text: <span style="font-size:120%; font-weight:550">이러한 분야에 관심이 있습니다<br></span>
      items:
        - name: <span style="font-size:110%; font-weight:bold">Database</span>
          description: |
            <span style="font-size:110%; font-weight:550">SQL을 통한 데이터베이스 설계 및 제어</span>
          icon: database
          icon_pack: fas
        - name: <span style="font-size:110%; font-weight:bold">Algorithm</span>
          description: |
            <span style="font-size:110%; font-weight:550">알고리즘을 이용한 보다 효율적인 서비스 설계</span>
          icon: gears
          icon_pack: fas
        - name: <span style="font-size:110%; font-weight:bold">Web</span>
          description: |
            <span style="font-size:110%; font-weight:550">서버/DB 통신 구조 및 관리</span>
          icon: chrome
          icon_pack: fab
    design:
      spacing:
        padding: ['5vh', 0, '5vh', 0]

  - block: features
    content:
      title: <span style="font-weight:bold">해보고 싶은 분야</span>
      subtitle: 
      text: <span style="font-size:120%; font-weight:550">배워보고 싶습니다</span>
      items:
        - name: <span style="font-size:110%; font-weight:bold">AI</span>
          description: |
            <span style="font-size:110%; font-weight:550">인공지능 모델 활용 개발 및 프로젝트</span>
          icon: brain
          icon_pack: fas
        - name: <span style="font-size:110%; font-weight:bold">Network Security</span>
          description: |
            <span style="font-size:110%; font-weight:550">보안 위협 차단을 통한 보안성 증진</span>
          icon: shield-halved
          icon_pack: fas
        - name: <span style="font-size:110%; font-weight:bold">Hardware</span>
          description: |
            <span style="font-size:110%; font-weight:550">컴퓨터 시스템의 이해를 통한 효율적인 개발</span>
          icon: hard-drive
          icon_pack: fas
    design:
      spacing:
        padding: ['5vh', 0, '7vh', 0]

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
      view: community/custom-compact
      columns: 1
    archive:
      enable: true
      text: See all blog posts
      link: post/

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text="Contact →" %}}
    design:
      columns: '1'
---
