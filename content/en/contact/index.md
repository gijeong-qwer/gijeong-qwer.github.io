---
title: My page
type: landing

sections:
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: ''
      # Contact details - edit or remove options as needed
      email: gjakdoo@jbnu.ac.kr
      phone: 010-4614-9266
      appointment_url: 'https://calendly.com'
      address:
        street: 567 Baekje-daero, Deokjin-gu, Jeonju, Jeollabuk-do
        city: JeonJu
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: center of UNIV
      office_hours:
        -'I am available at any time.'
     
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/gjakdoo
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
      # Automatically link email and phone or display them just as text?
      autolink: true
      # Choose an email form provider (netlify/formspree)
      form:
        provider: netlify
        formspree:
          # If using Formspree, enter your Formspree form ID
          id: ''
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
      # Coordinates to display a map - set your map provider in `params.yaml`
      coordinates:
        latitude: '35.848292'
        longitude: '127.131965'
   
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---
