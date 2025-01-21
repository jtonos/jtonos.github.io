---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing


sections:
- block: resume-biography
    content:
      # The user's folder name in `content/authors/`
      username: admin
      # Show a call-to-action button under your biography? (optional)
      # To link to a file, upload it to your `static/uploads/` folder
    design:
      banner:
        # Upload a cover image to `assets/media/` folder and reference its filename here (optional)
        filename: lemur_harungana.jpg
      biography:
        # Customize the CSS style of your biography text (optional)
        style: font-size: 18px; line-height: 1.6; color: #555; font-family: Arial, sans-serif; text-align: justify;
        
  - block: hero
    content:
      title: Mutualisms in a Changing World
      image:
        filename: lemur_portrait.jpg
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
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'




---
