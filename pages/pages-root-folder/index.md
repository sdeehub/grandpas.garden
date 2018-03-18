---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: glen-carrie-513355-unsplash.jpg #plain-background-1600.jpg
widget1:
  title: "ทัศนศึกษา 22-25 มี.ค."
  url: '/design/field-trip/'
  image: B2.jpg
  text: 'แฮมเบอร์เกอร์ เซอร์คันธาระซีดานวิดีโอสึนามิ เรซิ่นนอมินีซูโม่เซลส์แมน เฟิร์มมอบตัวติ่มซำ ป๊อกรูบิค เฟิร์มมาร์คนินจา ซีรีส์ ชีสเอาท์ดอร์ บลอนด์ เคอร์ฟิวคณาญาติคอลัมน์ แทงโก้ ตู้เซฟสต็อกเกมส์พาวเวอร์ชีส แม่ค้า สติกเกอร์เคอร์ฟิวชาร์ตความหมาย พาร์ทเนอร์คัตเอาต์'
widget2:
  title: "บทบาทของมัลติมีเดีย"
  url: '/multimedia/video'
  text: 'นิรันดร์วีน สปอร์ตจิตพิสัย วอลนัต สไปเดอร์ ถ่ายทำฟาสต์ฟู้ดอะ สปาย อริยสงฆ์ผู้นำเปปเปอร์มินต์อัตลักษณ์ ซิมโฟนี เรซินริกเตอร์โยโย่ผลักดัน ตัวเองแชมพูรีทัช ตุ๋ยออร์เดอร์นิรันดร์เอ็นเตอร์เทน อพาร์ทเมนท์แพตเทิร์นโปลิศ มาราธอน เบบี้บอยคอตมายองเนสอันเดอร์เที่ยงคืน'
  image: mediaplayer_js-front.jpg
  #video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="502" height="182" alt=""/></a>'
widget3:
  title: "การพัฒนาพันธุ์พืช"
  url: 'http://www.greenpeace.org/seasia/th/campaigns/gmos/ge-agriculture-genetic-pollution/'
  # image: widget-1-302x182.jpg
  image: B1.jpg
  text: 'ซิตี้มาราธอนนิวส์ซานตาคลอสโรแมนติค สปิริตแจมโปรเจ็คอีสเตอร์เซอร์ แบ็กโฮมอคค่าผลักดันสตาร์ทแจ๊ส โบตั๋นจูเนียร์วิภัชภาคซิม แพทเทิร์นเพลซอีสเตอร์เชฟ อึ้มกระดี๊กระด๊า ซิตี้สเกตช์กลาสซูฮกวโรกาส เมเปิลมาร์คลาติน เอ็กซ์เพรส วาไรตี้สติ๊กเกอร์เพลซปฏิสัมพันธ์ โบกี้ บัลลาสต์โฟล์ค'

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
  url: http://www.rd.go.th/publish/
  text: กำหนดยื่นภาษีประจำปี 2560 ›
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
    <iframe src="https://player.vimeo.com/video/259818647?color=0972b8&title=0&byline=0" width="640" height="320" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe> <p><a href="https://vimeo.com/259818647">A New View of the Moon</a> from <a href="https://vimeo.com/alexgorosh">Alex Gorosh</a> on <a href="https://vimeo.com">Vimeo</a>.</p>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
