---
# Leave the homepage title empty to use the site title
title: DeBacker Research Group
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        DeBacker
        Research Group
      image:
        filename: Medications.jpg
      text: |
        <br>
        
        <b> Our Focus </b>
        Our research group studies the effects of medications on hearing, balance, and genetics. Currently, our focus is on medications called antiretrovirals that are used to manage and prevent HIV/AIDS.
  
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
