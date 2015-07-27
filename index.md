---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
# 
layout: frontpage
title: "Avoka Transact Building Blocks"
header:
   image_fullwidth: "header_unsplash_12.jpg"
widget-1:
    title: "How it works"
    url: 'getting-started/'
    text: 'How does this GitHub repo work and what can you do with the components on it.'
    image: unsplash_9-302x182.jpg 
widget-2:
    title: "Finnovate Video"
    url: 'https://www.youtube.com/watch?v=HenZZz3bvJY&feature=youtu.be'
    text: 'Our award winning <em>Finnovate</em> demo with Derek'
    video: '<a href="#" data-reveal-id="videoModal"><img src="/images/BestofAward.png" width="302" height="182" alt=""></a>'
widget-3:
    title: "Download Components"
    url: '/blog/'
    text: 'Browse and download the collection of components. Don''t forget to contribute and give back to this community.'
    image: github-303x182.jpg
---


<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
      <iframe width="1280" height="720" src="https://www.youtube.com/embed/HenZZz3bvJY" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>