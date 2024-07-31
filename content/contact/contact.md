---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: false #true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  email: healix.loo@gmail.com
  phone: 6828
  address:
    street: Beutenbergstraße 11
    city: Jena
    region: Thuringia
    postcode: '07745'
    country: Germany
    country_code: DE
  coordinates:
    latitude: '50.9271'
    longitude: '11.5892'
  directions: Enter Building 1 and take the stairs to Office II on Floor 2
  office_hours:
    - 'Monday-Friday 10:00 to 18:00'
    - 'Saturday 14:00 to 17:00'
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

Contact me by filling in the form below.
