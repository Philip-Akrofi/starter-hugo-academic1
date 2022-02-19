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
  email: p.akrofi@outlook.com
  phone:  +86 18650432427
  address:
    street: Zhongnan University of Economics and Law
    city: Wuhan
    region: Hubei
    postcode: '470020'
    country: China
    country_code: CN
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Zhongnan University of Economics and Law campus
  office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Friday 09:00 to 13:00'
  appointment_url: ''
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: linkedin
      icon_pack: person
      name: Connect
      link: 'linkedin.com/in/philip-akrofi-atitianti'

design:
  columns: '2'
---
