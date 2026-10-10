---
# Leave the homepage title empty to use the site title
title:
date: 2026-10-10
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
      title: Family and Fertility
      sort_by: Weight
      order: asc
      count: 0
      filters:
        folders:
          - publication
          - workinprogress
        tag: 'Family and Fertility'
        exclude_featured: false
    design:
      columns: '1'
      view: citation

  - block: collection
    content:
      title: Education and Human Capital
      sort_by: Weight
      order: asc
      count: 0
      filters:
        folders:
          - publication
          - workinprogress
        tag: 'Education and Human Capital'
        exclude_featured: false
    design:
      columns: '1'
      view: citation

  - block: collection
    content:
      title: Macroeconomics and Labor Markets
      sort_by: Weight
      order: asc
      count: 0
      filters:
        folders:
          - publication
          - workinprogress
        tag: 'Macro and Labor Markets'
        exclude_featured: false
    design:
      columns: '1'
      view: citation

  - block: collection
    content:
      title: Policy Papers
      count: 0
      filters:
        folders:
          - policy
        exclude_featured: false
    design:
      columns: '1'
      view: citation

  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: |
        **Macroeconomics I** (undergraduate) — Universidad de los Andes, 2026–present.
    design:
      columns: '1'
---
