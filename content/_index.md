---
# Leave the homepage title empty to use the site title
title:
date: 2023-07-24
type: landing

sections:
  - block: hero
    content:
      title: |
        spatialHeatmap
      image:
        filename: visual_abs.jpg
      text: |
        <br>
        <p>The spatialHeatmap software visualizes spatial bulk and single cell assays in anatomical images.</p>
        <span><b>Getting started: </b></span>
        <div>
        <img class='icon' src='r.jpg'><a href="https://bioconductor.org/packages/devel/bioc/html/spatialHeatmap.html" target="_blank" style='margin:5px'>Bioconductor</a></img>
        <img class='icon' src='shiny.jpg'><a href="https://tgirke.shinyapps.io/spatialHeatmap/" target="_blank" style='margin:5px'>Shiny App</a></img>
        </div>
        <style>
        #section-hero.home-section.wg-hero { padding-bottom:10px }
        img.icon {
          width: 12%; border-radius: 0%; display: inline-block;
         }
         img.article-banner {
           width: auto;
           display: none; margin-left: auto; margin-right: auto;
         }
        </style>
  - block: collection
    content:
      title: Functionalities
      subtitle:
      text: |
        <style>
        #section-collection {display:none}
        </style>
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1' 
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        <div><center>
        <span style='font-size: 1.35rem;'>Quick Start</span><br/>
        <span >Click on the images to open the App at corresponding state:</span><br/>
        <a href="https://tgirke.shinyapps.io/spatialHeatmap/?_inputs_&ids=%22Apoh,Cav2%22&upl-fileIn=%22mouse_organs%22&dat-scl=%22No%22&dat-log=%22No%22&dat-normDat=%22CNF-TMM%22&shmAll-genCon=%22con%22&shmAll-scrollH=450&shmAll-scale.shm=1.1&shmAll-col.n=2&dat-sig.max=10000&dat-sig.min=-10000&dat-CV2=10000&dat-P=0&dat-A=0&scell-covisAuto-filBlkCV2=200&scell-covisAuto-filBlkCV1=0.1&scell-covisAuto-filBlkA=1&scell-covisAuto-filBlkP=0.1&scell-covisMan-filBlkCV2=200&scell-covisMan-filBlkCV1=0.1&scell-covisMan-filBlkA=1&scell-covisMan-filBlkP=0.1" target="_blank" style='margin:5px'><img class='screenshot' src='shm_bk.png' style='width: 25%;'></img></a>
        <a href="https://tgirke.shinyapps.io/spatialHeatmap/?_inputs_&ids=%22YAB5%22&upl-fileIn=%22arab_rootRoot%22&dat-scl=%22No%22&dat-log=%22No%22&dat-normDat=%22None%22&shmAll-genCon=%22gene%22&shmAll-scrollH=450&shmAll-scale.shm=1.1&shmAll-col.n=2&dat-sig.max=10000&dat-sig.min=-10000&dat-CV2=10000&dat-P=0&dat-A=0&scell-covisAuto-filBlkCV2=200&scell-covisAuto-filBlkCV1=0.1&scell-covisAuto-filBlkA=1&scell-covisAuto-filBlkP=0.1&scell-covisMan-filBlkCV2=200&scell-covisMan-filBlkCV1=0.1&scell-covisMan-filBlkA=1&scell-covisMan-filBlkP=0.1" target="_blank" style='margin:5px'><img class='screenshot' src='shm_arab_bk.jpg' style='width: 14%;'></img></a>
        <a href="https://tgirke.shinyapps.io/spatialHeatmap/?_inputs_&ids=%22Adcy1,Actr3b%22&upl-fileIn=%22covis_mouse_brain%22&dat-scl=%22No%22&dat-log=%22No%22&dat-normDat=%22None%22&shmAll-genCon=%22gene%22&shmAll-scrollH=500&shmAll-scale.shm=1.1&shmAll-col.n=2&dat-sig.max=10000&dat-sig.min=-10000&dat-CV2=10000&dat-P=0&dat-A=0&scell-covisAuto-filBlkCV2=200&scell-covisAuto-filBlkCV1=0.1&scell-covisAuto-filBlkA=1&scell-covisAuto-filBlkP=0.1&scell-covisMan-filBlkCV2=200&scell-covisMan-filBlkCV1=0.1&scell-covisMan-filBlkA=1&scell-covisMan-filBlkP=0.1" target="_blank" style='margin:6px'><img class='screenshot' src='covis_bk.png', style='width: 45.5%;'></img></a>
        </center></div>
        <style>
          #section-markdown.home-section {padding: 2px}
          img.screenshot {
            border: 1px solid #6c757d; border-radius: 5%; display: inline-block;
          }
        </style>
    design:
      columns: '1'
---


