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
      text:
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
        - title: Database Systems teaching assistant senior
          company: Università Ca' Foscari Venezia
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2022-12-01'
          date_end: ''
          description: ''
        - title: Algorithms and Data Structures teaching assistant senior
          company: Università Ca' Foscari Venezia
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2022-09-01'
          date_end: ''
          description: ''
        - title: Discrete Math teaching assistant
          company: Università Ca' Foscari Venezia
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2022-09-01'
          date_end: ''
          description: ''
        - title: Database Systems teaching assistant
          company: Università Ca' Foscari Venezia
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2022-03-01'
          date_end: '2022-06-30'
          description: ''
        - title: Cryptography teacher for CyberChallenge.IT 2022
          company: Università Ca' Foscari Venezia
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2022-03-01'
          date_end: '2022-06-30'
          description: ''
        - title: Algorithms and Data Structures teaching assistant senior
          company: Università Ca' Foscari Venezia
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2021-12-01'
          date_end: '2022-05-30'
          description: ''
        - title: Discrete Math teaching assistant
          company: Università Ca' Foscari Venezia
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2021-09-01'
          date_end: '2022-01-30'
          description: ''
        - title: Cryptography and Software Security teacher for CyberChallenge.IT 2021
          company: Università Ca' Foscari Venezia
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2021-03-01'
          date_end: '2021-06-30'
          description: ''
        - title: Linear Algebra teaching assistant
          company: Università Ca' Foscari Venezia
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2020-09-01'
          date_end: '2021-01-30'
          description: ''
        - title: Research intern
          company: Università Ca' Foscari Venezia
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2020-11-01'
          date_end: '2021-01-31'
          description: ''
        - title: Research fellow in Adversarial Machine Learning
          company: Università Ca' Foscari Venezia
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2020-12-01'
          date_end: '2021-04-30'
          description: ''
        - title: Research intern
          company: Università Ca' Foscari Venezia
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2020-03-20'
          date_end: '2020-09-30'
          description: ''
        - title: Trainee - Web Development
          company: Ennova Research S.r.l. 
          company_url: ''
          company_logo: ''
          location: 'Mestre/Venice'
          date_start: '2020-02-15'
          date_end: '2020-03-15'
          description: ''
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
      #text: |-
      #  {{% callout note %}}
      #  Quickly discover relevant content by [filtering publications](./publication/).
      #  {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: aaaaaaa
    content:
      title: aaaaaaaa
      date_format: Jan 2006
      items:
        - date_start: '2022-10'
          organization: Journal of Computer Security
          organization_url: ''
          title: Reviewer
          title: External reviewer
        - date_start: '2021-11'
          organization: EuroS&P
          organization_url: ''
          title: External reviewer
        - date_start: '2022-05'
          organization: ACSAC
          organization_url: ''
          title: External reviewer
    design:
      columns: '2'
      view: compact
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - talks
    design:
      columns: '2'
      view: compact
---
