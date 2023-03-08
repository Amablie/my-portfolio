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
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas
  - block: experience
    content:
      title: Education
      items:
      - title: Bsc in Statistic & Probability
        company: Federal University of Paraná
        company_url: https://www.ufpr.br/portalufpr/
        company_logo: null
        location: Curitiba
        date_start: "2018-02-15"
        date_end: ''
        description: "  Responsibilities include:\n  \n  Monitoring and organization
          of activities, developing teaching, research, and extension projects as a
          Scholarship holder at PET - Statistic."
    design:
      columns: '2'          
  - block: experience
    content:
      title: Experience
      items:
      - title: Data Analytics
        company: Solvay
        company_url: https://www.solvay.com/en/
        company_logo: null
        location: Curitiba
        date_start: "2021-12-15"
        date_end: ''
        description: "  Responsibilities include:\n\n  - Process automation and data
          extraction, assisting in the elaboration of analyzes and decision-making in
          the financial sector;\n  - Support in the maintenance of reports and dashboards
          (Qliksense and Data Studio), being a technical point of contact and helping
          global teams in their daily activities;\n  - Database extraction obtained
          through extensive databases, for manipulation and treatment in order to assist
          in decision making;\n  - Search for new data-driven solutions and improvements
          for the Credit team.\n  "
      - title: Business Intelligence
        company: Mirum Agency
        company_url: https://www.mirumagency.com.br/
        company_logo: null
        location: Curitiba
        date_start: "2020-02-17"
        date_end: "2021-12-08"
        description: "  Responsibilities include:\n\n  - Market research and information
          gathering using tools such as Google Analytics, Facebook Analytics, and other
          digital marketing tools\n  - Development of dashboards using DataStudio, helping
          in the automation of processes and facilitating metric analysis\n  - Database
          update and manipulation using Excel, Google Sheets, and BigQuery queries\n
          \ - Preparation of reports and presentations using PowerPoint and DataStudio.\n
          \ "
      - title: Credit Modeling (intern)
        company: Bradesco
        company_url: https://banco.bradesco/html/classic/index.shtm
        company_logo: null
        location: Curitiba
        date_start: "2019-07-17"
        date_end: "2019-11-08"
        description: "  Responsibilities include:\n\n  - Manipulation and approval of
          databases using SAS and Excel\n  - Organization of spreadsheets and documents\n
          \ - Assistance in preparing presentations"
    design:
      columns: '2'
      
  - block: accomplishments
    content:
      title: Accomplish&shy;ments
      subtitle: null
      date_format: Jan 2006
      items:
      - certificate_url: https://www.datacamp.com
        date_end: ''
        date_start: "2022-12-25"
        description: ''
        organization: DataCamp
        organization_url: https://www.datacamp.com
        title: Manipulating Time Series Data in R
        url: ''
      - certificate_url: https://www.datacamp.com
        date_end: "2020-12-21"
        date_start: "2020-07-01"
        description: ''
        organization: DataCamp
        organization_url: https://www.datacamp.com
        title: Understanding Data Science
        url: ''
      - certificate_url: https://www.datacamp.com
        date_end: "2020-12-21"
        date_start: "2020-07-01"
        description: ''
        organization: DataCamp
        organization_url: https://www.datacamp.com
        title: Intermediate SQL Queries
        url: ''
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
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
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
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
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
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
      text: |-
        Contact me.
      # Contact (add or remove contact options as necessary)
      email: amabilegaldin11@gmail.com
      phone: +55 (41) 991752952
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      contact_links:
        # - icon: twitter
        #   icon_pack: fab
        #   name: DM Me
        #   link: 'https://twitter.com/Twitter'
        # - icon: skype
        #   icon_pack: fab
        #   name: Skype Me
        #   link: 'skype:echo123?call'
        # - icon: video
        #   icon_pack: fas
        #   name: Zoom Me
        #   link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
