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
      text: |-
        My research interests are computer science applied to ecology.
        My favorite subject is the use of computer science to assist ecosystem management.
        I believe that computer models can help us better understand ecological successions and community assembly by formalising their branching behaviour.
        I am both interested in formal ecological theories and practical applications. 
    design:
      spacing:
        padding: ["3%", "0", "11%", "0"]
      background:
        image:
          # Name of image in `assets/media/`.
          filename: about_banner.png
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: 100%
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: bottom
          parallax: false
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
          company: "[IBISC](https://www.ibisc.univ-evry.fr/) and [AMAP](https://amap.cirad.fr/fr/index.php)"
          company_logo: 'graduation-cap'
          location: Evry and Montpellier, France
          date_start: '2019-11-01'
          date_end: '2022-12-12'
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
        featured_only: true
      archive:
        enable: true
        text: See all my publications
        link: publication/
    design:
      columns: '2'
      view: community/mypub
---
