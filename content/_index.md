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
      columns: '2'
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
          company: [IBISC](https://www.ibisc.univ-evry.fr/) & [AMAP](https://amap.cirad.fr/fr/index.php)
          company_url: ''
          company_logo: ''
          location: Evry & Montpellier, France
          date_start: '2019-11-01'
          date_end: '2022-10-31'
          description: Analyse de graphes état-transition d’écosystèmes
à l’aide de model-checking
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
      view: citation
---
