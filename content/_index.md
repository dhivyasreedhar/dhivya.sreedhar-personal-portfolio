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
        - title: Software Developer
          company: Zoho Corporation
          company_url: 'https://www.manageengine.com/cloud-siem/features/cloud-based-log-management.html'
          company_logo: ZOHO
          location: Chennai, India
          date_start: '2022-08-18'
          date_end: ''
          description: |2-
              
              * Part of the Manage Engine - Log360 Cloud OD Team
              * Using ember js, Java, MySQL tech stack
              * Worked on the search page feature enhancement of the product

              
        - title: Programmer Analyst Trainee Intern
          company: Cognizant Technology Solutions
          company_url: 'https://www.cognizant.com/us/en/services/ai'
          company_logo: Cognizant's_logo
          location: Chennai, India
          date_start: '2022-01-01'
          date_end: '2022-08-01'
          description: |2-
            * Part of the Artificial Intelligence and Analytics (AIA) - Informatica Cloud Team
            * Analysed and tested Data warehousing techniques, ETL tools
            * Created various mappings using Infomatica Powercenter, IICS
        - title: Undergraduate Researcher
          company: SRM Easwari Engineering College
          company_url: 'https://srmeaswari.ac.in/'
          company_logo: 
          location: Chennai, India
          date_start: '2021-05-01'
          date_end: '2022-12-01'
          description: |2-
            Research intern under Prof. KPK Devan, Dept of Computer Science and Engineering:
            * Worked on a fake tweet detection system that detects fake tweets related to COVID 19
            * Extracted tweets related to COVID 19 using tweepy and the twitter API
            * Developed an LSTM based model to detect fake tweets using NLP
        
        - title: Summer Research Intern
          company: NIT Calicut
          company_url: 'http://www.nitc.ac.in/'
          company_logo: nitc_logo_icon
          location: India
          date_start: '2021-06-01'
          date_end: '2021-07-01'
          description: |2-
            Research intern under Prof. Prabu Mohandas, Dept of Computer Science and Engineering:
            * Developed a Music Instrument Recognition System
            * Built CNN and KNN models and analysed their performance
            * Both models performed with accuracy above 90%
        
            
    design:
      columns: '2'
  - block: accomplishments
    id: online courses
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Online Courses'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://drive.google.com/file/d/1tkQCa9aGsiyZMbrh6n93l3CdUydZLqwN/view
          date_end: ''
          date_start: '2021-01-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Object Oriented Data Structures in C++
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org 
          title: Audio Classification with Tensorflow
          url: 
        - certificate_url: https://drive.google.com/file/d/1kM3I5KKqnrRmU7yKPczZG08qh4IQCVrX/view?usp=sharing
          date_end: ''
          date_start: '2021-01-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org 
          title: What is Data Science?
          url: ''
        - certificate_url: https://drive.google.com/file/d/1nkUZCe6FgNVjQ2Mxr9tL0Lz3m-Jw4y5E/view?usp=sharing
          date_end: ''
          date_start: '2021-01-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org 
          title: Introduction to Tensorflow for Artificial Itelligence, Machine Learning and Deep Learning
          url: ''
        # - certificate_url:
        #   date_end: ''
        #   date_start: '2021'
        #   description: ''
        #   organization:
        #   organization_url: 
        #   title: ''
        #   url: '' 
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
      
  
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      #text: |-
       #Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: dhivyasreedhar@gmail.com
      phone: +91 9677021836
      
        
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
