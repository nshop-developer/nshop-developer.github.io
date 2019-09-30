---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: main.png
widget1:
  title: "Right now!"
  url: 'https://recruit.navercorp.com/naver/job/list/developer?searchSysComCd=&entTypeCd=&searchTxt=%EB%84%A4%EC%9D%B4%EB%B2%84+%EC%87%BC%ED%95%91'
  image: widget-3-302x182.jpg
  text: '네이버 쇼핑에선 많은 개발자 여러분들을 적극 모시고자 합니다! <br/> 항상 즐겁고 새롭게 일할 수 있는, 지금 바로 지원하세요!'  
widget2:
  title: "DEVIEW 2019"
  url: 'https://deview.kr/2019/schedule/281'
  image: widget-2-302x182.jpg
  text: '매해 NAVER 에서 진행하는 국내 최대 개발자 컨퍼런스 중 하나인 DEVIEW 에 네이버 쇼핑이 참여합니다! <br/> 10월 10일 부터 접수로 많은 관심 부탁드립니다.' 
widget3:
  title: "First Meet Up"
  url: '/2019/09/28/showroom'
  image: widget-1-302x182.jpg
  text: '지난 2019년 9월 6일엔 네이버 쇼핑에서 처음으로 개발자 밋업인 <em>SHOWROOM::쇼핑개발자를 부탁해</em> 을 개최하였습니다. 많은 분들이 와주신 뜨거운 열기 속으로 함께 가보시죠?' 

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
callforaction:
  url: https://tinyletter.com/NAVER_SHOPPING
  text: Inform me about new updates and features ›
  style: alert
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
