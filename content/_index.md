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
  - block: features
    content:
      title: Skills
      items:
        - name: Python
          description: Python for data wrangling, data visualization, data analysis, machine learning, deep learning and web scraping.
          icon: python
          icon_pack: fab
        - name: R
          description: Basic knowledge of the basic library and the tidyverse packages.
          icon: r-project
          icon_pack: fab
        - name: SQL
          description: PostgreSQL for data query, data management and data definition.
          icon: sql
          icon_pack: custom
        - name: Excel
          description: Advanced Excel, VBA and Power Pivot.
          icon: excel
          icon_pack: custom
        - name: Power BI
          description: Power Query, DAX and dashboards.
          icon: power_bi
          icon_pack: custom
        - name: LaTeX
          description: ''
          icon: latex
          icon_pack: custom
  # - block: experience
  #   content:
  #     title: Experience
  #     # Date format for experience
  #     #   Refer to https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many `experience` items below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: CEO
  #         company: GenCoin
  #         company_url: ''
  #         company_logo: org-gc
  #         location: California
  #         date_start: '2021-01-01'
  #         date_end: ''
  #         description: |2-
  #             Responsibilities include:

  #             * Analysing
  #             * Modelling
  #             * Deploying
  #   design:
  #     columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.credential.net/4241c445-b2a5-4101-93a8-8931150153c4#gs.i1jvce
          date_end: ''
          date_start: '2022-11-06'
          description: 'The certificate program requires an understanding of building TensorFlow models using Computer Vision, Convolutional Neural Networks, Natural Language Processing, and real-world image data and strategies.'
          organization: TensorFlow
          organization_url: https://www.tensorflow.org/
          title: 'Tensorflow Developer Certificate'
          url: ''
        - certificate_url: https://basno.com/q5ozqcz5/
          date_end: ''
          date_start: '2021-03-01'
          description: 'Covers the essentials of finance, ethics, and investment roles, providing a clear understanding of the global investment industry'
          organization: CFA Institute
          organization_url: https://www.cfainstitute.org/
          title: 'Investment Foundations Certificate Holder'
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/Z52QNA7QRTQF
          date_end: ''
          date_start: '2022-08-01'
          description: 'In this Specialization, you will build and train neural network architectures such as Convolutional Neural Networks, Recurrent Neural Networks, LSTMs, Transformers, and learn how to make them better with strategies such as Dropout, BatchNorm, Xavier/He initialization, and more.'
          organization: DeepLearning AI
          organization_url: https://www.coursera.org/
          title: 'Deep Learning Specialization'
          url: https://www.coursera.org/specializations/deep-learning
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/XM862FC8VXUT
          date_end: ''
          date_start: '2022-10-01'
          description: 'It provides a broad introduction to modern machine learning, including supervised learning , unsupervised learning and some of the best practices used in Silicon Valley for artificial intelligence and machine learning innovation.'
          organization: DeepLearning AI
          organization_url: https://www.coursera.org/
          title: 'Machine Learning Specialization'
          url: https://www.coursera.org/specializations/machine-learning-introduction
        - certificate_url: https://www.credly.com/badges/e15e82cd-30c8-458e-b178-a1a8c415ccc0/public_url
          date_end: ''
          date_start: '2022-11-01'
          description: 'This introductory course is intended for students who seek an overall understanding of cloud computing concepts, independent of specific technical roles. It provides a detailed overview of cloud concepts, AWS core services, security, architecture, pricing, and support.'
          organization: AWS
          organization_url: https://aws.amazon.com/?nc1=h_ls
          title: 'Cloud Foundations'
          url: ''
        - certificate_url: https://portal.bloombergforeducation.com/certificates/3Trc8vd6B73HMXb65CKQ6uHJ
          date_end: ''
          date_start: '2020-04-01'
          description: 'BMC consists of 3 sections ??? Core Concepts (includes four modules ??? Economic Indicators, Currencies, Fixed Income, Equities), Getting Started on the Terminal and Portfolio Management.'
          organization: Bloomberg
          organization_url: https://www.bloomberg.com/professional/expertise/education/
          title: 'Bloomberg Market Concepts Certificate'
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
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      #title: Contact
      #subtitle:
      #text: #|-
      #  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: angel.lizaldi@gmail.com
     # phone: 888 888 88 88
     # appointment_url: 'https://calendly.com'
     # address:
      #  street: 450 Serra Mall
      #  city: Stanford
      #  region: CA
      #  postcode: '94305'
      #  country: United States
      #  country_code: US
    #  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    #  office_hours:
     #   - 'Monday 10:00 to 13:00'
     #   - 'Wednesday 09:00 to 10:00'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
