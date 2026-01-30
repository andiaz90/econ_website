---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      username: admin
      text:

  - block: collection
    id: research
    content:
      title: Working Papers
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '1'
      view: citation

  - block: collection
    content:
      title: Work in Progress
      sort_by: Weight
      order: asc
      count: 0
      filters:
        folders:
          - workinprogress
        exclude_featured: false
    design:
      columns: '1'
      view: citation
---
