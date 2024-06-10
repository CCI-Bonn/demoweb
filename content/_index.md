---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
editable: true

sections:
  - block: hero
    content:
      title: |
        About Us
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Computational Radiology & Clinical AI (CCI) at Bonn** has been an excellent research group in the intersection of AI and Radiology.
  
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
      page_type: event
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
<style>
        .twitter-timeline-container {
            direction: rtl; /* Set direction to right-to-left */
        }
        .twitter-timeline {
            text-align: left; /* Override text alignment */
        }
    </style>
<div class="twitter-timeline-container">
<a class="twitter-timeline" href="https://twitter.com/MICCAI_Society?ref_src=twsrc%5Etfw" style="display: none;">Tweets by MICCAI_Society</a>
</div>
 <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>