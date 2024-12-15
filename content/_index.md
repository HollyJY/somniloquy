---
# Leave the homepage title empty to use the site title
title:
date: 2024-12-15
type: landing

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
          filename: covers/cover1.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  
  - block: collection
    content:
      title: 福至心灵时刻
      subtitle:
      text:
      count: 2
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: 'hint'
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
---