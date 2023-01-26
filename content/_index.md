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
      text: My research interests are computer science applied to ecology.
    design:
      background:
        image:
          # Name of image in `assets/media/`.
          filename: about_banner.png
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: 100%
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: bottom
          parallax: true
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PhD
          company: IBISC and AMAP
          company_url: https://amap.cirad.fr/fr/index.php
          company_logo: ''
          location: Evry and Montpellier, France
          date_start: '2019-11-01'
          date_end: '2022-10-31'
          description: Analysis of state-transition graphs of ecosystems using model-checking
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: list
---
