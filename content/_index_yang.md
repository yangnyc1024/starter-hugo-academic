---
# Leave the homepage title empty to use the site title
title:
date: 2023-05-26
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
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
        - title: AI Research Scientist
          company: MunichRe/ HSB
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2021-12'
          date_end: 'Present'
          description: ''
        - title: Visiting Researcher /Adjunt Professor
          company: Stevens Institute of Technology
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2020-08'
          date_end: '2021-12'
          description: ''
    design:
      columns: '2'
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
---
