---
# Leave the homepage title empty to use the site title
title: Blended AI Research Group
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Blended AI Research Group
      image:
        filename: rcbm.png
      text: |
        <br>
        
        The **Blended AI Research Group** is an international research center specialized in **trustworthy AI**
        models integrating interpretable, neural-symbolic, and deep learning systems.
  
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
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
