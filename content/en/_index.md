---
# Leave the homepage title empty to use the site title
title:

type: landing

sections:
  - block: slider
    content:
      slides:
        - title: | 
            <span style="font-size:80%; font-weight:600;">Hello, I am Hyunsol Choi, a university student developer.</span>
          content: <span style="font-weight:600;">Welcome to my Portfolio!</span>
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
        - title: <span style="font-size:80%; font-weight:600;">Introduction</span>
          content: <span style="font-weight:600;">Let me introduce myself</span>
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
        - title: <span style="font-size:80%; font-weight:600;">My interests</span>
          content: <span style="font-weight:600;">Let me introduce my areas of interest</span>
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
        - title: <span style="font-size:80%; font-weight:600;">Projects</span>
          content: <span style="font-weight:600;">Various experiences and projects have been posted</span>
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
        - title: <span style="font-size:80%; font-weight:600;">Feedback and Others</span>
          content: <span style="font-weight:600;">Feedback and inquiries are welcome</span>
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
          My name is Choi Hyun-sol, and I am majoring in Computer Science at Jeonbuk National University.<br>
          I am studying to become a competent backend developer.
        </span>
        </div>
    design:
      spacing:
        padding: [0, 0, 0, 0]
 
  - block: features
    content:
      title: <span style="font-weight:bold">Current Interests</span>
      subtitle: 
      text: <span style="font-size:120%; font-weight:550">Interested in these fields<br></span>
      items:
        - name: <span style="font-size:110%; font-weight:bold">Database</span>
          description: |
            <span style="font-size:110%; font-weight:550">Database Design and Control using SQL</span>
          icon: database
          icon_pack: fas
        - name: <span style="font-size:110%; font-weight:bold">Algorithm</span>
          description: |
            <span style="font-size:110%; font-weight:550">More Efficient Service Design Using Algorithms</span>
          icon: gears
          icon_pack: fas
        - name: <span style="font-size:110%; font-weight:bold">Web</span>
          description: |
            <span style="font-size:110%; font-weight:550">Server/Database Communication Architecture and Management</span>
          icon: chrome
          icon_pack: fab
    design:
      spacing:
        padding: ['5vh', 0, '5vh', 0]

  - block: features
    content:
      title: <span style="font-weight:bold">Want to try</span>
      subtitle: 
      text: <span style="font-size:120%; font-weight:550">Would like to learn</span>
      items:
        - name: <span style="font-size:110%; font-weight:bold">AI</span>
          description: |
            <span style="font-size:110%; font-weight:550">Development and Projects Utilizing AI Models</span>
          icon: brain
          icon_pack: fas
        - name: <span style="font-size:110%; font-weight:bold">Network Security</span>
          description: |
            <span style="font-size:110%; font-weight:550">Enhancing Security through Threat Mitigation</span>
          icon: shield-halved
          icon_pack: fas
        - name: <span style="font-size:110%; font-weight:bold">Hardware</span>
          description: |
            <span style="font-size:110%; font-weight:550">Efficient Development through Understanding Computer Systems</span>
          icon: hard-drive
          icon_pack: fas
    design:
      spacing:
        padding: ['5vh', 0, '7vh', 0]

  - block: collection
    content:
      title: <strong>Recent Posts</strong><br><br>
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
         padding: ['5vh', '50px', '7vh', '50px']
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
