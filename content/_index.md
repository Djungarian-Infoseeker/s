---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Infoseeker
      image:
        filename: welcome.png
      text: |
        <br>
        
        **Infoseeker** is Yinjie Wang's new online alias, and there will also be the name of my personal website. The name Infoseeker, an abbreviation for 'information seeker', is inspired by the search engine company Infoseek where Robin Li, a fellow alumnus from my high school, Yangquan No.1 Middle School, and the president of Baidu, worked in his early career. This to a certain extent reflects my personal interests and hobbies, which include searching for various types of information and integrating them to abstract issues.
  
# - block: collection
#   content:
#     title: Latest News
#     subtitle:
#     text:
#     count: 5
#     filters:
#       author: ''
#       category: ''
#       exclude_featured: false
#       publication_type: ''
#       tag: ''
#     offset: 0
#     order: desc
#     page_type: post
#   design:
#     view: card
#     columns: '1'

  - block: slider
    content:
      slides:
      - title: 👋 Welcome to my website
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Lunch & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: World-Class Semiconductor Lab
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
  

  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="More info about me →" %}}
    design:
      columns: '1'
---