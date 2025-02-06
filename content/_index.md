---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
#      # Show a call-to-action button under your biography? (optional)
#      button:
#        text: Download CV
#        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'My Research'
      subtitle: ''
      text: |-
        Humans encounter vast amounts of information at every moment. The ability to perform complex mental computations and adapt flexibly to the changing environments constitutes the core of human cognition, and underlies higher-level cognition such as inference, language comprehension, and problem solving. The primary objective of my lab is to understand the neural mechanisms underlying such complex and flexible behaviors.  

        Our research integrates functional magnetic resonance imaging (fMRI), scalp electroencephalography (EEG), magnetoencephalography (MEG), intracranial EEG (iEEG), with psychophysics and computational modeling, to investigate the neural mechanisms underlying visual and high-level cognition. Specifically, we focus on the following areas:  

        1. Working memory
        We are interested in the neural mechanism of working memory, the ability to maintain and manipulate information in mind for a short period of time in order to serve current behavior demands. Previous work has suggested a distributed cortical network in working memory, including sensory, parietal, and frontal cortex; yet the respective contribution of these cortical regions in working memory has remained elusive. We approach this question by asking how memory maintenance and manipulation are differentially supported by the distributed cortical network? 

        2. Mental imagery
        Humans can construct rich internal experiences even in the absence of external sensory input. How do we generate vivid visual imagery in our brain? How does internally-constructed mental imagery differ from perceptual and mnemonic experiences derived externally? 

        3. Cognitive control and abstract representation
        Both working memory and mental imagery rely on abstract representations of knowledge and concepts. Abstract representations provide a basis for fast, effective learning and generalization during flexible behaviors. We are particularly interested how abstract information (such as concrete and abstract structural information) is represented in working memory and imagery to facilitate behavior. Along this line of research, we aim to elucidate how working memory and long-term memory interact in the brain. 
    design:
      columns: '1'
  #- block: collection
  #  id: papers
  #  content:
    #  title: Featured Publications
    #  filters:
    #    folders:
    #      - publication
    #    featured_only: true
    #design:
    #  view: article-grid
    #  columns: 2
#  - block: collection
#    content:
#      title: Publications
#      text: ""
#      filters:
#        folders:
#          - publication
#        exclude_featured: false
#    design:
#      view: citation
  - block: markdown
    content:
      title: 'Positions'
      subtitle: ''
      text: |-
        I am actively seeking talented postdocs and graduate students to join the lab. Please email me with your CV if you are interested!
    design:
      columns: '1'
  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    view: article-grid
  #    columns: 1
  #- block: collection
  #  id: news
  #  content:
  #    title: Recent News
  #    subtitle: ''
  #    text: ''
  #    # Page type to display. E.g. post, talk, publication...
  #    page_type: post
  #    # Choose how many pages you would like to display (0 = all pages)
  #    count: 5
  #    # Filter on criteria
  #    filters:
  #      author: ""
  #      category: ""
  #      tag: ""
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ""
  #    # Choose how many pages you would like to offset by
  #    offset: 0
  #    # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #  design:
  #    # Choose a layout view
  #    view: date-title-summary
  #    # Reduce spacing
  #    spacing:
  #      padding: [0, 0, 0, 0]

---
