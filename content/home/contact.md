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
  email: p.akrofi@stu.zuel.edu.cn
  phone:  +86 18650432427
  address:
    street: 182# Nanhu Avenue, East Lake High-tech Development Zone
    city: Wuhan
    region: Hubei
    postcode: '470020'
    country: China
    country_code: CN
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Building 10, Internatinoal Education School
  contact_links:
    - icon: linkedin
      icon_pack: person
      name: Linkedln
      link: 'linkedin.com/in/philip-akrofi-atitianti'

design:
  columns: '2'
---
