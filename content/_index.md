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
        A central challenge in cognitive neuroscience is to understand how humans learn, think, and explore the world with remarkable flexibility and adaptability. The primary objective of my laboratory is to elucidate the neural and computational mechanisms underlying this human intelligence, by integrating neuroimaging techniques (functional MRI, EEG, MEG, intracranial EEG), with behavioral measurements and computational modeling. Our research primarily focuses on the online computations supporting goal-directed, flexible cognition, a capacity subserved by the mental workspace of working memory. We further investigate higher cognitive functions that closely interact with working memory, including mental imagery, cognitive control, and long-term memory, to build a comprehensive model of how the brain enables the adaptive behavior and conscious thought that define human experience.  

        1. Working memory
        
        We are interested in the neural mechanism of working memory, the ability to maintain and manipulate information in mind for a short period of time in order to serve current behavioral demands. Previous work has suggested a distributed cortical network supporting working memory, including sensory, parietal, and frontal cortex; yet the respective contribution of these cortical regions has remained elusive. We aim to elucidate the distributed and adaptive nature of working memory.

        2. Mental imagery
        
        Humans can construct rich internal experiences even in the absence of external sensory input. How do we generate vivid imagery experiences in our brain? How does internally-constructed mental imagery differ from perceptual and mnemonic experiences derived externally? 

        3. Cognitive control and Abstraction
        
        Both working memory and mental imagery rely on abstract representations of knowledge and concepts. Abstract representations provide a foundation for fast, effective learning and generalization during flexible behaviors. We are particularly interested how abstract information (such as task rule or structural information) is represented in working memory and imagery. Along this line of research, we aim to elucidate how working memory and long-term memory interact in the brain. 
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
