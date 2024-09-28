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
  - block: collection
    content:
      filters:
        folders:
          - blog
    design:
     grid:
        columns: 2 # 2열로 설정
        gap: 20px # 카드 사이 간격 설정
        style: |
          display: grid;
          grid-template-columns: repeat(2, 1fr);
          gap: 20px;
          padding: 20px;
      spacing:
        padding: ['3rem', 0, '6rem', 0]
     

---
