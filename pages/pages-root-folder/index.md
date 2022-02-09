---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header-unsplash-001.jpg
widget1:
  title: "Love Letters"
  # url: 'http://phlow.github.io/feeling-responsive/blog/'
  url: 'http://mysimpleboy.github.io/blog/'
  image: love-letter.jpg
  text: '总写小作文真是让人讨厌，可是我管不住自己，总是想记录下来些什么，将我的爱打包好小心翼翼再落笔。'
widget2:
  title: "Anniversary video"
  url: 'https://github.com/mysimpleboy/mysimpleboy.github.io/'
  text: '这是我给你制作的三个月纪念视频，我曾经说过要给你一个惊喜，这个视频只是很小的一部分'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://mysimpleboy.github.io/images/love-unsplash.jpg" width="302" height="200" alt=""/></a>'

  # mysimpleboy.github.io/images/love-unsplash.jpg

  
widget3:
  title: "Movies"
  # url: 'https://github.com/Phlow/feeling-responsive'
  url: 'https://mysimpleboy.github.io/movies/'
  image: widget-github-303x182.jpg
  text: '记录一下我们在一起看过的电影，随着时间的推移，好像我们已经很少在一起欣赏完一部电影了。'
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

#callforaction:
  # url: https://tinyletter.com/feeling-responsive
  #url: https://www.jianshu.com/p/9f71e260925d
  #text: love you
  #style: alert

permalink: /index.html


###
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <!-- <iframe width="1280" height="720" src="https://www.bilibili.com/video/BV1N741177Ga" frameborder="0" allowfullscreen></iframe> -->
    <iframe src="//player.bilibili.com/player.html?aid=508867519&bvid=BV1Ju41197aw&cid=500750736&page=1&high_quality=1&danmaku=0" allowfullscreen="allowfullscreen" width="100%" height="500" scrolling="no" frameborder="0" sandbox="allow-top-navigation allow-same-origin allow-forms allow-scripts"></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>




