---
title: My page
hide_date: true
type: landing

#sections:
#  - block: resume-biography
#    content:
#      # The user's folder name in content/authors/
#      username: admin
#    design:
#      spacing:
#       padding: [0, 0, 0, 0]
#      biography:
#        style: 'text-align: justify; font-size: 0.8em;'
#  - block: collection
#    content:
#      filters:
#        folders:
#          - blog
#    design:
#      spacing:
#        padding: ['3rem', 0, '6rem', 0]

sections:
  - block: portfolio
    id: projects
    content:
      title: Projects
      subtitle: My subtitle
      text: hello world
      filters:
        # Folders to display content from
        folders:
          - blog
        # Only show content with these tags
        tags: ["API","WEB"]
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---
