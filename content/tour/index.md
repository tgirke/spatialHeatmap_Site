---
title: Tour
date: 2022-10-24

type: landing

sections:
  - block: slider
    content:
      slides:
      - title: Enrichment spatial heatmaps
        content: Detecting and visualizing tissue-selective spatial patterns
        align: center
        background:
          image:
            filename: input_image.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
          size: contain
          padding: ['20px', '0', '20px', '0']
      - title: Assay and image data
        content: ''
        align: center
        background:
          image:
            filename: data.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
          size: contain
      - title: Co-visualizing bulk and single-cell assay data
        content: ''
        align: center
        background:
          image:
            filename: output.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
          size: contain
      - title: Large-scale data mining
        content: 'Scaling analysis results in SHMs to large-scale data-mining'
        align: center
        background:
          image:
            filename: data_mining.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
          size: contain
      - title: Command-line and interactive implementation
        content: ''
        align: center
        background:
          image:
            filename: impl.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
          size: contain
        #link:
        #  icon: graduation-cap
        #  icon_pack: fas
        #  text: Contact Us
        #  url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
  - block: markdown 
    content:
      title: 
      subtitle: 
      text: | 
        <style>
        #section-markdown { display:none }
        .carousel-item.fullscreen {background-size: 50% !important;}
        .carousel-item.fullscreen.active {background-color: #ffffff !important;} 
        .position-absolute.d-flex.w-100.h-100 {backdrop-filter: brightness(1) !important;} 
        .wg-hero.dark.container {display:none; transform: translateY(-84%);} 
        .wg-hero.dark.container > * {color: black !important;}
        .carousel-control-next-icon, .carousel-control-prev-icon {filter: invert(1);}
        </style>
---
