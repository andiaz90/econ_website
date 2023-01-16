---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: collection
    id: workingpapers
    content:
      title: Working Papers
      # text: |-
      #   {{% callout note %}}
      #   Quickly discover relevant content by [filtering publications](./publication/).
      #   {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: andiaz@sas.upenn.edu
      # phone: +1 267 616 8132
      address:
        street: 133 South 36th Street
        city: Philadelphia
        region: PA
        postcode: '19104'
        country: United States
        country_code: US
      # Automatically link email and phone or display as text?
      autolink: true
    #   # Email form provider
    #   form:
    #     provider: netlify
    #     formspree:
    #       id:
    #     netlify:
    #       # Enable CAPTCHA challenge to reduce spam?
    #       captcha: false
    # design:
    #   columns: '2'
---
