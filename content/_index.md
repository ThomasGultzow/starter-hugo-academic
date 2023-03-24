---
# Leave the homepage title empty to use the site title
title: Thomas Gültzow
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
        - title: Assistant Professor in Social Psychology
          company: Maastricht Univeristy
          company_url: 'https://www.maastrichtuniversity.nl/'
          location: Maastricht, NL
          date_start: '2022-01-01'
          date_end: ''
        - title: PhD Candidate
          company: Maastricht Univeristy
          company_url: 'https://www.maastrichtuniversity.nl/'
          location: Maastricht, NL
          date_start: '2017-10-01'
          date_end: '2021-12-31'
          description: When Informed Decision Making Meets Health Promotion – An integration of both areas based on the example of smoking cessation
        - title: Paediatric Nurse
          company: Various hospitals and outpatient care services, including Clinics of Cologne (Kinderkrankenhaus Amsterdamer Straße
          location: Germany
          date_start: '2010-10-01'
          date_end: '2017-09-30'
          description: Includes vocational training
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
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
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
---
