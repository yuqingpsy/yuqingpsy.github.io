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
        Humans encounter massive amounts of information every day. The abilities to make effective selections on external input, to internally generate novel information in the absence of external input, to perform different levels of processing in different scenarios, and to make corresponding actions according to current task goals, constitute the core of human cognition, and underlie higher-level cognition such as inference, language comprehension, and problem solving. The primary interest of our lab is therefore to understand the neural mechanisms that underlie such complex and flexible behaviors.  

        Our work combines functional magnetic resonance imaging (fMRI), scalp electroencephalography (EEG), megnetoencephalography (MEG), intracranial EEG (iEEG), with psychophysics and computational modeling, to understand the neural mechanisms underlying visual and high-level cognition. Specifically:  

        1. We are interested in the neural mechanism of working memory, the ability to maintain and manipulate information in mind for a short period of time in order to serve current behavior demands. Previous work has suggested a distributed cortical network in working memory, including sensory, parietal, and frontal cortex; yet the respective contribution of these cortical regions in working memory has remained elusive. We approach this question by asking how memory maintenance and manipulation are differentially supported by the distributed cortical network of working memory? 

        2. Humans can construct rich internal experience, even in the absence of any external input. How do we generate vivid visual imagery in our brain? How is mental imagery different from perceptual and mnemonic experiences derived externally? 

        3. Both working memory and mental imagery rely on representations of abstract knowledge and concepts in the brain. Abstract representations provide a basis for fast, effective learning and generalization during flexible behaviors. We are particularly interested how abstract structural information (such as concrete and abstract contextual information) is represented in working memory and imagery to facilitate behavior. Along this line of research, we hope to start to understand how working memory and long-term memory interact in the brain. 
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
  - block: collection
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    content:
      title: 'Positions'
      subtitle: ''
      text: |-
        I am actively looking for talented postdocs and graduate students to join the lab.
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
