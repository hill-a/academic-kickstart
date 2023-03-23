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
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Machine Learning
          tag: Machine Learning
        - name: Raspberry Pi
          tag: Raspberry Pi
        - name: Python
          tag: Python
        - name: C/C++
          tag: C-Cpp
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
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
      text:
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
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
        - title: Research Engineer
          company: CEA
          company_url: ''
          company_logo: cea
          location: Palaiseau
          date_start: '2021-12-20'
          date_end: ''
          description: Researcher Engineer specialized in machine learning applied to robotics.
        - title: PhD in Machine Learning applied to Mobile Robots
          company: Université Clermont-Auvergne
          company_logo: UCA
          date_start: '2018-11-05'
          date_end: '2022-11-23'
        - title: PhD candidate
          company: CEA
          company_url: ''
          company_logo: cea
          location: Palaiseau
          date_start: '2018-11-05'
          date_end: '2021-12-20'
          description: Artificial Intelligence applied to Mobile Robots.
        - title: Research Intern
          company: ENSTA ParisTech - U2IS robotics lab
          company_url: 'http://u2is.ensta-paris.fr/'
          company_logo: ENSTA
          location: Palaiseau
          date_start: '2018-03-05'
          date_end: '2018-09-05'
          description: State representation learning for robotics.
        - title: MSci in Machine Learning, Information and Content
          company: Université Paris-Scalay
          company_logo: ParisSaclay
          date_start: '2016-09-01'
          date_end: '2018-09-05'
        - title: Magistaire in Computer Science
          company: Université Paris-Sud
          company_logo: UPSUD
          date_start: '2015-09-01'
          date_end: '2018-09-05'
        - title: Research Intern
          company: Laboratory for Computer Science
          company_url: 'https://www.lri.fr/'
          company_logo: LRI
          location: Saclay
          date_start: '2017-05-01'
          date_end: '2017-07-31'
          description: Experimental evaluation of performance criteria in machine learning.
        - title: BSc in Computer Science
          company: Université Paris-Sud
          company_logo: UPSUD
          date_start: '2012-09-01'
          date_end: '2016-06-01'
    design:
      columns: '2'
  - block: features
    content:
      title: Skills
      items:
        - name: python
          description: 90%
          icon: python
          icon_pack: fab
        - name: C/C++
          description: 95%
          icon: file-code
          icon_pack: fas
        - name: Ocaml
          description: 80%
          icon: file-code
          icon_pack: fas
        - name: ROS
          description: 90%
          icon: robot
          icon_pack: fas
        - name: Unix
          description: 95%
          icon: terminal
          icon_pack: fas
        - name: Docker
          description: 85%
          icon: docker
          icon_pack: fab
        - name: Machine Learning
          description: 85%
          icon: chart-line
          icon_pack: fas
        - name: Reinforcement Learning
          description: 95%
          icon: play
          icon_pack: fas
        - name: French & English
          description: Bilingual
          icon: language
          icon_pack: fas
        - name: Embedded programming
          description: 75%
          icon: microchip
          icon_pack: fas
        - name: Soldering
          description: 70%
          icon: user-edit
          icon_pack: fas
        - name: Electronic design
          description: 40%
          icon: memory
          icon_pack: fas
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      email: contact [at] hill-a [dot] me
      phone:
      appointment_url:
      address:
        street:
        city: Saclay
        region: Essones
        postcode: '91400'
        country: France
        country_code: FR
      contact_links:
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider:
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
