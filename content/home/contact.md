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
  email: 123456789@qq.com
  phone: 123456789
  address:
    street: 
    city: 郑州
    region: 河南
    postcode: '123456'
    country: 中国
    country_code: CHN
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: 到哪了，想办法联系我
  office_hours:
    - '工作日早上9点~晚上7点'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
