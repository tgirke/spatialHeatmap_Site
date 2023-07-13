---
title: Modules

# Listing view
view: compact

# Optional banner image (relative to `assets/media/` folder).
banner:
  caption: ''
  image: ''
---

<script>
var checkAvatar = setInterval(function(){
    let el = document.querySelector('.media.author-card');
    if(el) {el.remove(); clearInterval(checkAvatar);} 
}, 50);

var checkShare = setInterval(function(){
    let el = document.querySelector('.share-box');
    if(el) {el.remove(); clearInterval(checkShare);} 
}, 50);
var checkFooter = setInterval(function(){
    let el = document.querySelector('.site-footer p:nth-child(2)');
    if(el) {el.remove(); clearInterval(checkFooter);} 
}, 50);
</script>

