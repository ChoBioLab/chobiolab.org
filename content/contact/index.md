---
title: Contact
date: 2024-06-26

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-

      email: cholab@ibdgc.org
      phone: 888 888 88 88
      address:
        street: 1470 Madison Avenue, 8th Fl., Box 1498
        city: New York
        region: NY
        postcode: '10029'
        country: United States
        country_code: US
      coordinates:
        latitude: '40.7909'
        longitude: '-73.9517'
      directions: Enter Hess Center for Science and Medicine and take the elevator to floor 8
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      #appointment_url: 'https://calendly.com'
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
