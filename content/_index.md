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
        - name: Arduino
          description: Electric circuit programming language 
          icon: infinity
          icon_pack: fas
        - name: OnShape
          description: 3D modelling web application
          icon: cube
          icon_pack: fas
        - name: SolidWorks
          description: 3D modelling software
          icon: cubes
          icon_pack: fas
        - name: Lab skills
          description: Pipetting, Cell culturing, Hydrogel synthesis, Spectroscopy
          icon: flask-vial
          icon_pack: fas 
        - name: LaTeX
          description: Literature editting
          icon: bookmark
          icon_pack:  fas
        - name: Photography
          description: Nature and Food photograpy
          icon: camera-retro
          icon_pack: fas
  - block: experience
    content:
      title: Extracurricular Involvement
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2022
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Design Committee Member
          company: Penn Assistive Devices and Prosthetic Technologies (ADAPT)
          company_url: 'https://pennclubs.com/club/adapt'
          company_logo: adapt
          location: University of Pennsylvania
          date_start: '2022-09-01'
          date_end: ''
          description: |
            Attending workshops to learn required softwares, tools, and acquiring skills for designing biomedical devices and prosthetics to meet the needs of patients.
              Responsibilities: include:
              * Designing
              * Modelling
              * Building
        - title: Moonshot Factory Committee Member
          company: Wharton Undergraduate Healthcare Club (WUHC)
          company_url: 'https://www.wuhcpenn.org/'
          company_logo: 
          location: University of Pennsylvania
          date_start: '2022-09-01'
          date_end: ''
          description: |
            Providing assistance to Penn's students in the field of biology, medicine, bioengineering, and healthcare management by organizing workshops, pitch competitions, speaker events, and more.
        - title: Outreach Committee Member
          company: Kesem
          company_url: 'https://pennclubs.com/club/camp-kesem'
          parent company: 'https://www.kesem.org/'
          location: University of Pennsylvania
          date_start: '2022-09-01'
          date_end: ''
          description: |
            Raising funds to organize a summer camp for children impacted by their parent's cancer.
              Fund Raising activities:
                * Held a bake sale.
                * Participated in Messy Olympics.
                * Sold toast at the football game.
              Other responsibilities:
                * Writing cards to children.
                * Reaching out to schools in the West Philly area.
        - title: Member
          company: Wharton Undergraduate Entrepreneurship Club (WUEC)
          company_url: 'https://groups.wharton.upenn.edu/wuec/commitees/'
          location: University of Pennsylvania
          date_start: '2022-09-01'
          date_end: ''
          description: Attending general meetings, speaker events, and  workshops. 
      
        - title: Volunteer
          company: Netter Center for Community Partnerships
          company_url: 'http://www.nettercenter.upenn.edu/'
          location: University of Pennsylvania
          date_start: '2022-10-01'
          date_end: ''
          description: |
            Volunteer at the Lea School's in West Philadelphia.
              Responsibilities:
                Assisted in planning and set-up of a safe Halloween Trick-or-Treat event. ALso managed a table for donating candies to underprivileged children.
    design:
      columns: '2'
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
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
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
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
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
        <p>Let's Connect!</p>    
        
        <p>Whether it is about collaboration opportunities, inquiries, or just a friendly chat, feel free to reach out via any of the contact options below. Your message means a lot, and I will make sure to get back to you ASAP.</p>  
        
        <p>I am excited to hear from you!</p>    
      # Contact (add or remove contact options as necessary)
      email: patelsuhani07@gmail.com
      phone: +1-215-960-4462
      appointment_url: 'https://calendly.com/patelsuhani07'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/patel_suha92419'
        - icon: instagram
          icon_pack: fab
          name: Follow me on Instagram
          link: 'https://www.instagram.com/_suhani.patel_/'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://us04web.zoom.us/j/4197634798?pwd=O6mUzY7RM6u1wNn6bJIShRmGfbJvfB.1'
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
