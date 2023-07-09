---
title: Contact
date: 2023-07-01

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Please contact us if you have any questions regarding our research or open positions!
      email: bonnspatialmemorylab@gmail.com
      phone: +49 228 287 19369
      address:
        street: Venusberg Campus 1
        city: Bonn
        region: NRW
        postcode: 53127
        country: Germany
        country_code: GER
      coordinates:
        latitude: '50.700330'
        longitude: '7.103620'
      directions: Enter the Clinic of Epileptology and take the stairs to the second floor
      office_hours:
        - 'Monday 08:00 to 18:00'
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
        provider: googlemail # netlify
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
