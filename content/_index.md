---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
#   - block: hero
#     content:
#       title:
#       image:
#         filename:
# #      cta:
# #        label: '**Get Started**'
# #        url: https://wowchemy.com/templates/
# #      cta_alt:
# #        label: Ask a question
# #        url: https://discord.gg/z8wNYzb
# #      cta_note:
# #        label: >-
# #          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-themes" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Wowchemy Website Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
#       text:
# ----------------- Image Break ----------------- #
  - block: markdown
    content:
      title:
      subtitle: ''
      text: |-
        {{% callout note %}}
        Website Under Development! Please Excuse Any Bugs 🐛
        {{% /callout %}}
        </n>
    design:
        background:
         image:
          # Name of image in `assets/media/`.
          filename: colorful-smoke.jpg
          # Apply image filters?
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 0
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true

# ----------------- Biography ----------------- #
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

# ----------------- Skills ----------------- #
  - block: features
    content:
      title: Skills
      items:
        - name: Coding
          description: Python, Jupyter, MATLAB, Wolfram Mathematica
          icon: python
          icon_pack: fab
        - name: Modeling
          description: SolidWorks, COMSOL Multiphysics, Simpleware ScanIP
          icon: cubes
          icon_pack: fas
        - name: Experimental
          description: SEM, FFT Analysis, Additive Manufacturing, Laser Cutting, DMA
          icon: vial
          icon_pack: fas
        - name: Imaging
          description: DSLR, PIV (Planar and Volume), Motion Tracking
          icon: camera
          icon_pack: fas
        - name: Technical Writing
          description: Project Reports, SOPs, Proposals, Conference Posters/Presentations, Publications
          icon: book
          icon_pack: fas
        - name: Misc. Software
          description: Adobe Suite, LabView, VSCode
          icon: window-restore
          icon_pack: fas

# ----------------- Experience ----------------- #
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
        - title: Graduate Research Assistant
          company: University of Nevada, Las Vegas
          company_url: 'https://www.kwangjinkim.org/'
          company_logo: UNLV-Scarlet
          location: Las Vegas, Nevada
          date_start: '2018-06-01'
          date_end: ''
          description: |2-
              Active Materials and Smart Living (AMSL) Lab

              Responsibilities include:
              - [x] Researched electroactive polymers (EAPs), focusing on ionic polymer-metal composites (IPMCs) and their use as flexible fluid flow sensors for naval and underwater applications.
              - [x] Communicated directly with multiple vendors for acquiring and configuring substantial equipment related to the experimental setup for ONR Grant N00014-16-1-2356.
              - [x] Modeled with CAD software and utilized additive manufacturing for experimental testing platforms.
              - [x] Fabricated EAP actuators and sensors in a wet laboratory environment for applications in soft robotics and flow sensing.
              - [x] Developed physics-based models using COMSOL software for fluid-structure interaction studies, and vortex shedding for a MEMS vortex flowmeter.
              - [x] Design of experiments and data acquisition for various EAP actuators and sensors.
              - [x] Utilized various imaging and image processing techniques; including the development of a computer vision-based software in Wolfram Mathematica for tracking sensor deflection, travel velocity, and vortex shedding. 
              - [x] Lead on Particle Imaging Velocimetry (PIV) equipment attainment and setup. Wrote Standard Operating Procedure and implemented safety protocols for use.
        - title: Visiting Research Assistant
          company: Korea Institute of Science and Technology
          company_url: 'https://eng.kist.re.kr/eng/index.do'
          company_logo: KIST Logo
          location: Seoul, South Korea
          date_start: '2019-06-20'
          date_end: '2019-07-10'
          description: |2-
              Soft Mechatronics (SM) & Robotics Lab

              Responsibilities include:
              - [x] Collaborated with a multinational team in South Korea researching soft-robotics and artificial muscles at the Korea Advanced Institute of Science and Technology (NSF Grant #1545857).
              - [x] Fabricated and modeled a piezoelectric energy harvesting ring-type transducer comprised of a PVDF film supported by a PDMS substrate
              - [x] Fabricated EAP actuators and sensors in a wet laboratory environment for applications in soft robotics and flow sensing.
              - [x] Designed and assembled a testing apparatus for the energy harvester ring, along with a fingerbending model using additive manufacturing and laser cutting.
    design:
      columns: '2'

  # ----------------- Accomplishments ----------------- #
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: News #'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'

  # ----------------- Blog Posts ----------------- #
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'

# ----------------- Image Break ----------------- #
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
        background:
         image:
          # Name of image in `assets/media/`.
          filename: colorful-smoke.jpg
          # Apply image filters?
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 0
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true

  # ----------------- Projects ----------------- #
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
      # buttons:
      #   - name: All
      #     tag: '*'
      #   - name: Deep Learning
      #     tag: Deep Learning
      #   - name: Other
      #     tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: card
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  
  # ----------------- Gallery ----------------- #
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'

  # ----------------- Featured Publications ----------------- #
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

  # ----------------- Recent Publications ----------------- #
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
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  
  # ----------------- Conference Talks ----------------- #
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

  # ----------------- Tag Cloud ----------------- #
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  
  # ----------------- Image Break ----------------- #
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
        background:
         image:
          # Name of image in `assets/media/`.
          filename: colorful-smoke.jpg
          # Apply image filters?
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 0
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true

  # ----------------- Contact ----------------- #
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: nazanin.minaian@gmail.com
      phone: (702) 744-7082
      appointment_url: ''
      address:
        street: 4505 S Maryland Pkwy
        city: Las Vegas
        region: NV
        postcode: '89154'
        country: United States
        country_code: US
      directions: Office 2173 - Please request permission from downstairs help desk to visit 2nd floor.
      office_hours:
      contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
#          link: 'https://twitter.com/Twitter'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#        - icon: video
#          icon_pack: fas
#         name: Zoom Me
#         link: 'https://zoom.com'
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
