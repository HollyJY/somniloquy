---
# Title, summary, and page position.
title: ✍️ 随便扯点，或者月记
linktitle: ✍️ 日日夜夜
summary: 月记和随笔
weight: 3
# icon: python
# icon_pack: fab

# Page metadata.
date: '2023-07-07T00:00:00Z'
toc: false
---

---
title: My page
type: landing

sections:
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: 'Check out my recent blog posts below!'
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: card

---
