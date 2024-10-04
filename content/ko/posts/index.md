---
title: 
type: landing

# Optional banner image (relative to `assets/media/` folder).
banner:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/)'
  image: 'post.jpg'

sections:
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          caption: 'Image credit: [**Unsplash**](https://unsplash.com/)'
          filename: post.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']

    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: collection
    content:
      title: <span style="font-weight:bold; text-aligh:center">전체 포스트</span><br><br>
      subtitle: 
      text: 
      count: 0
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
  - block: tag_cloud
    content:
      title: <span style="font-weight:bold">태그</span>
      subtitle:
      text: 태그에 따라 분류된 포스트를 확인하실 수 있습니다.
      # Choose a taxonomy from the `taxonomies` list in `config.yaml` to display (e.g. tags, categories, authors)
      taxonomy: tags
      # Choose how many tags you would like to display (0 = all tags)
      count: 0
    design:
      # Minimum and maximum font sizes (1.0 = 100%).
      font_size_min: 2.0
      font_size_max: 3.5

---
