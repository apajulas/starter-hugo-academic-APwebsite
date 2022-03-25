---
# An instance of the Contact widget.

widget: contact # Documentation: https://sourcethemes.com/academic/docs/page-builder/
headless: true # This file represents a page section.
weight: 150 # Order that this section appears on the page.

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

design:
  columns: '2'
---
