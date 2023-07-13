---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
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
        <p>The spatialHeatmap software is specialized in visualizing spatial bulk and single cell assays in anatomical images. Check the <a href="https://bioconductor.org/packages/devel/bioc/html/spatialHeatmap.html" target="_blank">command-line</a> and the <a href="https://tgirke.shinyapps.io/spatialHeatmap/" target="_blank">interactive</a> implementation of this software.</p>

  - block: collection
    content:
      title: Modules
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
---
