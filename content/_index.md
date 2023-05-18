---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        SKY@Lugano
      image:
        filename: welcome.png
      text: |
        <br>
        
        SKY@Lugano promotes physical and mental well-being of the student community through scientific breathwork and meditation techniques.
  
  - block: collection
    content:
      title: Latest on SKY
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
      page_type: news
    design:
      view: compact
      columns: '1'
  
  - block: markdown
    content:
      title: "At Stanford, we have found that SKY Campus Happiness has played an important role in improving overall student well-being."
      subtitle: '– Director, <br>
      Wellness & Health Promotion Services <br>
      Stanford University'
      text: "This is a <span class='white-text'>word</span> with white text color."
    design:
      columns: '1'
      background:
        image: 
          filename: PeopleMeditating.webp
          filters:
            brightness: 0.7
          parallax: false
          position: center
          size: large
          text_color_light: true
      spacing:
        padding: ['20px', '20px', '20px', '20px']
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