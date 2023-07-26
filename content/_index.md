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
        <p>The spatialHeatmap software is specialized in visualizing spatial bulk and single cell assays in anatomical images. 
        <div>
        <img class='icon' src='r.jpg'><a href="https://bioconductor.org/packages/devel/bioc/html/spatialHeatmap.html" target="_blank" style='margin:5px'>Bioconductor</a></img>
        <img class='icon' src='shiny.jpg'><a href="https://tgirke.shinyapps.io/spatialHeatmap/" target="_blank" style='margin:5px'>Shiny App</a></img>
        </div>
  - block: collection
    content:
      title: Functionalities
      subtitle:
      text:
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
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        <style>
        img.icon {
          width: 15%; border-radius: 0%; display: inline-block;
         }
         img.article-banner {
           width: auto;
           display: none; margin-left: auto; margin-right: auto;
         }
        </style>
---
