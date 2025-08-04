---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  # ... existing sections ...
  
  - block: markdown
    id: pi-highlight
    content:
      title: 'Principal Investigator'
      subtitle: 'Research Group Leader'
      text: |
        Meet **Dr. [Your Name]**, Professor of [Department] and leader of the Shi Photonics Group. 
        With over [X] years of experience in nanophotonics research, Dr. [Name] has published 
        [X] papers and received [major awards/grants].
        
        [{{< cta cta_text="Learn More" cta_link="/pi/" >}}]
    design:
      columns: '1'
  
  - block: markdown
    id: join-us
    content:
      title: 'Join Our Team'
      subtitle: 'Open Positions Available'
      text: |
        We're looking for motivated **postdocs**, **graduate students**, and **undergraduates** 
        to join our research in nanophotonics. Multiple funded positions available.
        
        [{{< cta cta_text="View Openings" cta_link="/join/" >}}]
    design:
      columns: '1'
      background:
        color: 'navy'
        text_color_light: true
    
  - block: hero
    content:
      title: |
        Wowchemy
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Wowchemy Research Group** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.
  
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

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
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
