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
  email: jhou27@asu.edu
  phone: +1 (480) 546-2167
  address:
    street: Business Administration C-wing, 300 E Lemon St
    city: Tempe
    region: AZ
    postcode: '85281'
    country: United States
    country_code: US
  coordinates:
    latitude: '33.4255'
    longitude: '111.9400'
  directions:  Office 609 on Floor 6

design:
  columns: '2'
---
