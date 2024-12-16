---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  # - block: hero
  #   content:
  #     title: |
  #       Wowchemy
  #       Research Group
  #     image:
  #       filename: welcome.jpg
  #     text: |
  #       <br>
        
  #       The **Wowchemy Research Group** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: covers/cover1.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
#          size: cover
          spacing:
            padding: ['-20px', '0', '-20px', '0']
          text_color_light: true
      css_class: fullscreen

# 最近有意思想法
  - block: collection
    content:
      title: ⚗️ 好东西
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: 'moment'
      offset: 0
      order: desc
      page_type: moments
    design:
      view: card
      columns: '1'

---