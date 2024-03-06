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
        
        **Infoseeker** is Yinjie Wang's new online alias, and there will also be the name of his personal website. The name Infoseeker, an abbreviation for 'information seeker', is inspired by the search engine company Infoseek where Robin Li, a fellow alumnus from my high school, Yangquan No.1 Middle School, and the president of Baidu, worked in his early career. This to a certain extent reflects my personal interests and hobbies, which include searching for various types of information and integrating them to abstract issues.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  #- block: markdown
  #  content:
  #    title:
  #    subtitle: ''
  #    text:
  #  design:
  #    columns: '1'
  #    background:
  #      image: 
  #        filename: coders.jpg
  #        filters:
  #          brightness: 1
  #        parallax: false
  #        position: center
  #        size: cover
  #        text_color_light: true
  #    spacing:
  #      padding: ['20px', '0', '20px', '0']
  #    css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="More info about me →" %}}
    design:
      columns: '1'
---