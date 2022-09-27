---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  email: lid@idsse.ac.cn
  phone: 17854222428
  address:
    street: No. 28, Luhuitou Road
    city: Sanya
    region: Hainan
    postcode: '572000'
    country: CHINA
    country_code: CN
  coordinates:
    latitude: '18.21089'
    longitude: '109.47506'
  directions: Enter Comprehensive Building and take the stairs to Office 509 on Floor 5
  office_hours:
    - 'Weekday 8:30 to 17:30'
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
---

