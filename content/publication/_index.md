---
title: Publications

# Listing view
view: citation

# Optional banner image (relative to `assets/media/` folder).
banner:
  caption: ''
  image: ''
# The following section does not work.
sections:
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        <style>
        .universal-wrapper {display:none !important}
        </style>
---

<script>
var checkAvatar = setInterval(function(){ 
    let el = document.querySelector('.universal-wrapper');
    if(el) {
      // Remove example publications.
      $('.universal-wrapper').remove()
      // Add new publications.
      $( ".page-body" ).append("<div id='vig' style='width:1000px;margin-top:10px;margin-left:auto;margin-right:auto;padding-left:1rem;padding-right:1rem;text-align:justify'><b style='font-size:1.2rem'>Software Vignettes</b> <br/></div>" );
      $( ".page-body" ).append("<div id='vig' style='width:1000px;margin-top:10px;margin-left:auto;margin-right:auto;padding-left:1rem;padding-right:1rem;font-size:0.8rem;text-align:justify'><span>1. Visualizing Spatial Assays in Anatomical Images and Large-Scale Data Extensions. <a href='https://www.bioconductor.org/packages/release/bioc/vignettes/spatialHeatmap/inst/doc/spatialHeatmap.html' target='_blank'>[link]</a> <br/>2. Co-visualizing Bulk and Single-cell Assay Data. <a href='https://www.bioconductor.org/packages/release/bioc/vignettes/spatialHeatmap/inst/doc/covisualize.html' target='_blank'>[link]</a></span> <br/></div>");
      $( ".page-body" ).append("<div id='vig' style='width:1000px;margin-top:10px;margin-left:auto;margin-right:auto;padding-left:1rem;padding-right:1rem;text-align:justify'><b style='font-size:1.2rem'>Publications</b> <br/></div>" );
      $(".page-body").append("<div id='pub2' style='width:1000px;margin-top:10px;margin-left:auto;margin-right:auto;padding-left:1rem;padding-right:1rem;font-size:0.8rem;text-align:justify'>1. Zhang J, Zhang L, Gongol B, Hayes J, Borowsky AT, Bailey-Serres J, Girke T (2024) spatialHeatmap: visualizing spatial bulk and single-cell assays in anatomical images. NAR Genomics and Bioinformatics: 6, 1-18. <a href='https://pubmed.ncbi.nlm.nih.gov/38312938/' target='_blank'>[PubMED]</a> <br/></div> ");
      $(".page-body").append("<div id='pub3' style='width:1000px;margin-top:10px;margin-left:auto;margin-right:auto;padding-left:1rem;padding-right:1rem;font-size:0.8rem;text-align:justify' >2. Reynoso MA, Borowsky AT, Pauluzzi GC, Yeung E, Zhang J, Formentin E, Velasco J, Cabanlit S, Duvenjian C, Prior MJ, Akmakjian GZ, Deal RB, Sinha NR, Brady SM, Girke T, Bailey-Serres J (2022) Gene regulatory networks shape developmental plasticity of root cell types under water extremes in rice. Dev Cell: 57, 1177-1192. <a href='https://pubmed.ncbi.nlm.nih.gov/35504287/' target='_blank'>[PubMed]</a><br/></div> ");
      clearInterval(checkAvatar);
    } 
}, 50);


/*
// Remove hyper links.
var checkAvatar = setInterval(function(){ 
    let el = document.querySelector('a');
    if(el) {
      $("a").removeAttr("href"); clearInterval(checkAvatar);
    } 
}, 50);

var checkAvatar = setInterval(function(){ 
    let el = document.querySelector('.universal-wrapper');
    if(el) {el.remove(); clearInterval(checkAvatar);} 
}, 50);

*/
</script>

