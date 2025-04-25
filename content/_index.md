---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  # - block: hero
  #   content:
  #     title: |
  #       <h1>Shaping The Next Interaction</h1>
  #     text: |
  #       The **Interactive TEchnology & Methodology Laboratory** is an interdisciplinary research group in the Department of Software Convergence at Kyung Hee University. 

  #       Our research focuses on **designing novel input and output interfaces fostering seamless interactions** between humans and computers.
  #   design:
  #     column: 1
  #     background:
  #         image: 
  #           filename: landing.jpg
  #         filters:
  #           brightness: 0.3
  #           parallax: false
  #           position: center
  #     # spacing:
  #     # # Customize the section spacing. Order is top, right, bottom, left.
  #     # padding: ['20px', '0', '20px', '0']
      
  - block: hero
    content:
      title: |
        Shaping The Next Interaction
      text: |
        The **Interactive TEchnology & Methodology Laboratory** is an interdisciplinary research group in the Department of Software Convergence at Kyung Hee University. 

        Our research focuses on **designing novel input and output interfaces fostering seamless interactions** between humans and computers.
      image:
        filename: landing.jpg
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 4 
      filters:
        author: 'admin'
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
# 참고: https://docs.hugoblox.com/getting-started/page-builder/#listing-view      
    design:
      view: compact #card, citation, list, showcase
      columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---
