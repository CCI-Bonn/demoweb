---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
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
