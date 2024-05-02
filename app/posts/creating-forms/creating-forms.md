---
layout: collection
title: Creating forms
description: A way for teachers and would-be teachers to access many DfE services with one login
pagination:
  data: collections.creating-forms
  reverse: true
  size: 50
permalink: "creating-forms/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
override:tags:
  - post
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: Home
related:
  sections:
    - title: Related content
      items:
        - text: "DIA Prototype (password: gai)"
          href: https://get-an-identity-prototype.herokuapp.com/
        - text: Prototype repository
          href: https://github.com/DFE-Digital/get-an-identity-prototype
---