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
  email: mge@umass.edu
  address:
    street: 80 Campus Center Way
    city: Amherst
    region: MA
    postcode: '01002'
    country: United States
    country_code: US
  coordinates:
    latitude: '42.391155'
    longitude: '72.526711'
  directions: Stockbridge Hall, Floor 4
  contact_links:
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://umass-amherst.zoom.us/j/7050599466'

design:
  columns: '2'
---
