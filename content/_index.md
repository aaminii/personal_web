---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
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
        - title: "PhD Researcher"
          company: "University of Manchester / Cockcroft Institute"
          company_url: ''
          company_logo: ''
          location: "Warrington, UK"
          date_start: '2023-09-01'
          date_end: '2027-03-31'
          description: |2-
             Responsibilities include:

             * Develop numerical models and simulations of electron-beam dynamics using Python and MATLAB.
             * Analyse experimental and simulation data to extract physical parameters, correlations, and performance metrics.
             * Validate and optimise models using experimental data, sensitivity analysis, and automated Python workflows.
        - title: "Master's thesis"
          company: "ICMUV Institute"
          company_url: ''
          company_logo: icmuv
          location: "Valencia, Spain"
          date_start: '2023-03-20'
          date_end: '2023-08-20'
          description: "Modeling ultra-high accelerating gradients in carbon-based nanostructures through an effective plasma-density approach."
        - title: "Practical Research"
          company: "CERN Institute"
          company_url: ''
          company_logo: cern-vector-logo
          location: "Geneva, Switzerland"
          date_start: '2023-02-04'
          date_end: '2023-02-28'
          description: |2-
             Responsibilities include:

             * RF measurement methods 
             * Beam diagnostics of CLEAR beamline
        - title: "Practical Research"
          company: "SOLEIL Institute"
          company_url: ''
          company_logo: logo_0
          location: "Saint-Aubin, France"
          date_start: '2022-10-01'
          date_end: '2023-01-31'
          description: |2-
             Responsibilities include:

             * Crystallography by Low Energy Electron Diffraction
             * Longitudinal Beam measurement at the SOLEIL synchrotron
        - title: "Practical Research"
          company: "INFN Institute"
          company_url: ''
          company_logo: infn
          location: "Frascati, Italy"
          date_start: '2022-03-01'
          date_end: '2022-07-30'
          description: |2-
             Responsibilities include:

             * Plasma Diagnostics for Plasma-based Accelerators
             * Image denoising by Artificial Intelligence
        - title: "Teaching assistant"
          company: "University of Manchester & Urmia University"
          company_url: ''
          company_logo: ''
          location: "Manchester, UK / Urmia, Iran"
          date_start: '2019-08-01'
          date_end: ''
          description: |2-
             Responsibilities include:

             * Delivered undergraduate Mathematical Physics tutorials and laboratory demonstrating.
             * Data analysis and student assessment evaluation.
    design:
      columns: '2'
  - block: accomplishments
    content:
      title: 'Achievements & Certifications'
      subtitle: ''
      date_format: Jan 2006
      items:
        - certificate_url: ''
          date_end: ''
          date_start: '2026-04-19'
          description: ''
          organization: "IPAC 2026"
          organization_url: ''
          title: "3rd Place - Hackathonino"
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2026-07-01'
          description: ''
          organization: "IOP PABG"
          organization_url: ''
          title: "Best Student Poster Prize"
          url: ''
        - certificate_url: 'https://www.se.manchester.ac.uk/phds-science-engineering/funding/deans-doctoral-scholarship/'
          date_end: ''
          date_start: '2023-09-05'
          description: ''
          organization: "Manchester University"
          organization_url: 'https://www.se.manchester.ac.uk/phds-science-engineering/funding/deans-doctoral-scholarship/'
          title: "Dean's Doctoral Scholarship"
          url: ''
        - certificate_url: 'https://www.master-lascala.eu/'
          date_end: '2023-09-01'
          date_start: '2021-09-01'
          description: ''
          organization: "Erasmus+"
          organization_url: 'https://erasmus-plus.ec.europa.eu/'
          title: "Erasmus Mundus Joint Masters scholarships for LASCALA program"
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2026-07-31'
          description: ''
          organization: "Advance HE"
          organization_url: ''
          title: "Associate Fellow of Advance HE (AFHEA)"
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2026-08-01'
          description: ''
          organization: "Online Certification"
          organization_url: ''
          title: "Using Machine Learning in Trading and Finance Certificate"
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2025-09-01'
          description: ''
          organization: "IBM"
          organization_url: ''
          title: "IBM Data Science Professional Certificate"
          url: ''
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: "Recent Posts"
      subtitle: ''
      text: ''
      count: 5
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      offset: 0
      order: desc
    design:
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: "Projects"
      filters:
        folders:
          - project
      default_button_index: 0
      buttons:
        - name: "Compact particle accelerators"
          tag: '*'
        - name: "THz acceleration"
          tag: THz
        - name: "NACANA"
          tag: NACANA
    design:
      columns: '1'
      flip_alt_rows: false

  - block: collection
    id: publication
    content:
      title: "Recent Publications"
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
  - block: contact
    id: contact
    content:
      title: "Contact"
      subtitle: ''
      text: ''
      email: "a.aminii@outlook.com"
      address:
        street: "Cockcroft Institute,Keckwick Ln"
        city: "Warrington"
        region: "Cheshire"
        postcode: "WA4 4AD"
        country: "United Kingdom"
        country_code: "UK"
      autolink: true
    design:
      columns: '2'
---
