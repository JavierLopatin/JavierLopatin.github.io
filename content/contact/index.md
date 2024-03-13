---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        We aim to create and maintain a diverse, inclusive and, above all, passionate remote sensing research group, committed to using what we learn to improve the world. We are committed to mentoring and supporting members of the group to achieve their career goals. If you have any questions about research opportunities, please don't hesitate to contact us.
      email: javier.lopatin@uai.cl
      phone: 9-72641924
      address:
        street: 450 Serra Mall
        city: Santiago
        region: RM
        postcode: '94305'
        country: Chile
        country_code: CH
      coordinates:
        latitude: '37.4275'
        longitude: '-122.1697'
      directions: Biulding E, office 313
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
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
