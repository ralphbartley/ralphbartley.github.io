---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: banner_home2.jpg
widget1:
  title: "Blog"
  url: 'https://forgedbyadria.com/blog/'
  image: studio_0-thumb.jpg
  text: "Explore Adria's thoughts on jewelry making"
widget2:
  title: "Jewelry Gallery"
  url: 'https://forgedbyadria.com/gallery/'
  image: gallery-thumb.jpg
  text: "Explore works Forged by Adria"
widget3:
  title: "About"
  url: 'https://forgedbyadria.com/about/'
  image: studio_2-thumb.jpg
  text: "Learn about the artist"
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>