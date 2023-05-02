---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👋 Welcome to the Adams group!
      content: Take a look at what we're working on...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.8
        media: Theta1.jpg
        
    - title: Genomic adaptation & ancestry
      content: We are developing a number of systems to test fundamental evolutionary hypotheses about rapid evolution in nature using native and invasive insects
      align: left
      background:
        position: left
        color: '#666'
        brightness: 0.5
        media: Span.jpg
        
        
    - title:  'Statistical Population Genomics: 
*predicting adaptation & ancestry*'
      content: 'We study population genomic variation using new predictive approaches for classifying genomic regions, predicting genetic ancestry, and reconstructing demography. We seek to apply these methods in several insect systems to illuminate the molecular basis of rapid adaptation.'
      align: right
      background:
        position: center
        color: '#666'
        brightness: 0.45
        media: FST.jpg
    - title: Data science in Genomics ☕️
      content: 'We are developing and applying an array of statistical learning algorithms for predicting drivers of functional trait evolution (e.g., gene expression), and models of genome evolution.'
      align: left
      background:
        position: center
        color: '#66'
        brightness: 0.4
        media: GG1.jpg

    - title:  'Mathematical & Algorithmic Phylogenetics: 
       
      
*putting the genome into phylogenomics*'
      content: 'We are developing and applying an array of new approaches for dissecting chromosome-scale variation in genealogical history, and for testing hypotheses concerning variation among individuals, populations, and species'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: Phylo1.jpg

    - title: Join us!
      content: 'We are actively recruiting undergraduate and graduate student researchers!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: Featured1.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
