---
widget: pages
headless: true
title: Recent blog posts
# Section subtitle
subtitle: By Alkemio Foundation
weight: 2

content:
    count: 5
    # Filter on criteria
    filters:
        # The folders to display content from
        folders:
            - post
        author: ""
        category: "Foundation"
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      

design:
    view: compact
    columns: '1'
    spacing:
        padding: ['30px', '0px', '40px', '0px']
    background:
      color: white
---