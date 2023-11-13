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

#   # Email form provider
#   form:
#     provider: netlify
#     formspree:
#       id:
#     netlify:
#       # Enable CAPTCHA challenge to reduce spam?
#       captcha: true

  # Contact details (edit or remove options as required)
  email: smkulinski@gmail.com
#   phone: 888 888 88 88
  contact_links:
  - icon: github
    icon_pack: fab
    link: https://github.com/SeanKski
    name: GitHub

  - icon: linkedin
    icon_pack: fab
    link: https://www.linkedin.com/in/seankulinski/
    name: LinkedIn

  address:
    street: San Fransisco
    city: Bay Area
    region: CA
    postcode: 
    country: United States
    country_code: US
#   coordinates:
#     latitude: '37.4275'
#     longitude: '-122.1697'
#   directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
#   office_hours:
    # - 'Monday 10:00 to 13:00'
    # - 'Wednesday 09:00 to 10:00'
#   appointment_url: 'https://calendly.com'

design:
  columns: '2'
---
