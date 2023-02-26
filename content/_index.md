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
    filters:
      exclude_featured: true
      folders:
      - publication
    title: Recent Publications
  design:
    columns: "2"
    view: citation
  id: publications
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
      - blogs
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Blogs
  design:
    columns: "2"
    view: compact
  id: blogs
- block: contact
  content:
    contact_links:
    email: matybr@umich.edu
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