---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
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

  # Contact details (edit or remove options as required)
  email: p.akrofi@live.com
  phone:  
  address:
    street: Xifeng 4th Road
    city: Xi'an
    region: Shaanxi
    postcode: '710000'
    country: China
    country_code: CN
  coordinates:
    latitude: '30.475224'
    longitude: '114.393532'
  directions: 
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: Linkedln
      link: 'linkedin.com/in/philip-akrofi-atitianti'

design:
  columns: '2'
---
