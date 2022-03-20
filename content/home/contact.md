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
      captcha: true

  # Contact details (edit or remove options as required)
  email: debaditya.pal6@gmail.com
  phone: (+91) 89810 69547
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: Let's connect
      link: "https://www.linkedin.com/in/debadityapal/"

design:
  columns: "2"
---
