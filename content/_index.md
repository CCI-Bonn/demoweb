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
  
  - block: people
    id: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigators
          - Senior Researchers
          - Researchers
          - Visiting Researchers
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

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

  - block: collection
    id: publication
    content:
      title: Publications
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
      page_type: publication
    design:
      view: citation
      columns: '1'
  
  - block: 'tweetx'
    content:
      title: 'Hello'
      subtitle: 'sub'
      text: 'hi'
    design:
      columns: '1'

  - block: contact
    id: contact
    content:
      title: Contact
      text: |-
        We're hiring and looking for research collaboration. Feel free to contact us. 
      email: contact@ccibonn.ai
      phone: +49 228 287-16505
      address:
        street: Venusberg-Campus 1, Building 81
        city: Bonn
        region: North Rhine-Westphalia
        postcode: '53127'
        country: Germany
        country_code: DE
      coordinates:
        latitude: '50.695805'
        longitude: '7.103828'
      directions: Enter Building 81 and Find Alex's office
      office_hours:
        - 'Weekdays: 9-5'
      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
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
          filename: contact.jpg
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

