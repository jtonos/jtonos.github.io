---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Mutualisms in a Changing World
      image:
        filename: welcome.jpg
      text: |
        <br>
        We study plant-animal interactions, with a particular focus on seed dispersal and frugivory. Many of our projects are geared towards documenting understudied interactions, assessing the structure of mutualisms at the individual-individual and species interaction levels, and examine how interactions are impacted by human-driven environmental change.
    design:
      view: card
      columns: '1'

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
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
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
          filename: lemur_harungana.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen


---
