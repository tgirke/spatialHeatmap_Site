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
      $( ".page-body" ).prepend("<div id='vig' style='width:90%;margin-top:10px;margin-left:10px;margin-right:10px;text-align:justify'>Main vignette of the software: <a href='https://www.bioconductor.org/packages/release/bioc/vignettes/spatialHeatmap/inst/doc/spatialHeatmap.html' target='_blank'>https://www.bioconductor.org/packages/release/bioc/vignettes/spatialHeatmap/inst/doc/spatialHeatmap.html</a> <br/></div>" );
      $(".page-body").append("<div id='pub2' style='width:90%;margin-top:10px;margin-left:10px;margin-right:10px;text-align:justify'><a href='https://academic.oup.com/nargab/article/6/1/lqae006/7597499?login=false' target='_blank'>1. Zhang J, Le Zhang, Gongol B, Hayes J, Borowsky AT, Bailey-Serres J, Girke T (2024). “spatialHeatmap: visualizing spatial bulk and single-cell assays in anatomical images.” NAR Genomics and Bioinformatics, 6(1), lqae006. ISSN 2631-9268, doi:10.1093/nargab/lqae006, https://doi.org/10.1093/nargab/lqae006.</a> <br/></div> ");
      $(".page-body").append("<div id='pub3' style='width:90%;margin-top:10px;margin-left:10px;margin-right:10px;text-align:justify' ><a href='https://www.cell.com/developmental-cell/fulltext/S1534-5807(22)00253-2?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS1534580722002532%3Fshowall%3Dtrue' target='_blank'>2. Reynoso MA, Borowsky AT, Pauluzzi GC, Yeung E, Zhang J, Formentin E, Velasco J, Cabanlit S, Duvenjian C, Prior MJ, Akmakjian GZ, Deal RB, Sinha NR, Brady SM, Girke T, Bailey-Serres J. Gene regulatory networks shape developmental plasticity of root cell types under water extremes in rice. Dev Cell. 2022 May 9;57(9):1177-1192.e6. doi: 10.1016/j.devcel.2022.04.013. Epub 2022 May 2. PMID: 35504287.</a><br/></div> ");
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

