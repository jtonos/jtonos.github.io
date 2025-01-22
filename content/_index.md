---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the Tonos Lab
        content: Our research focus is the study of mutualisms in a changing world.
        align: center
        background:
          image:
            filename: lemur_harungana.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Our publications
          url: ../publication/
      - title: Check out our lab news! 
        content: There you can find our latest research updates and opportunities for students and collaborators
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: News
          url: ../post/
      - title: Meet our Team! 
        content: 
        align: left
        background:
          image:
            filename: team_2017.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Lab members
          url: ../people/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: 800px
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 10000

  - block: hero
    content:
      title: Mutualisms in a Changing World
      image:
        filename: protrait_sml.jpg
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
      count: 1
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
---