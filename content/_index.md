---
date: "2022-10-24"
sections:
- block: about.avatar
  content:
    text: null
    username: admin
  id: about
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation
- block: contact
  content:
    contact_links:
    email: matybr@umich.edu
    form:
      formspree:
        id: null
      netlify:
        captcha: true
      provider: netlify
    subtitle: null
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---


   # address:
      city:
      country: United States
      country_code: US
      postcode: 
      region: 
      street: 
    contact_links: