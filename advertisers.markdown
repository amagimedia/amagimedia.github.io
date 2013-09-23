---
layout: default
title: advertisers
navigation: advertisers
clients:
- image: /img/amagi/advertisers/bikaji.jpg
  video: http://player.vimeo.com/video/74912280
  title: Bikaji
- image: /img/amagi/advertisers/arena.png
  video: http://player.vimeo.com/video/74912278
  title: Arena Multimedia
- image: /img/amagi/advertisers/yepme.png
  video: http://player.vimeo.com/video/74912309
  title: Yepme
- image: /img/amagi/advertisers/arena.png
  video: http://player.vimeo.com/video/74912308
  title: Raag Vanaspati
- image: /img/amagi/advertisers/lenskart.png
  video: http://player.vimeo.com/video/74912304
  title: Lenskart
- image: /img/amagi/advertisers/kidzee.png
  video: http://player.vimeo.com/video/74912302
  title: Kidzee
- image: /img/amagi/advertisers/honda.jpg
  video: http://player.vimeo.com/video/74912301
  title: Honda Motors
- image: /img/amagi/advertisers/hcl.png
  video: http://player.vimeo.com/video/74912298
  title: HCL Computers
- image: /img/amagi/advertisers/carbon.jpg
  video: http://player.vimeo.com/video/74912294
  title: Forever Diamonds
- image: /img/amagi/advertisers/finolex.jpg
  video: http://player.vimeo.com/video/74912292
  title: Finolex
- image: /img/amagi/advertisers/dpauls.png
  video: http://player.vimeo.com/video/74912289
  title: DPauls
- image: /img/amagi/advertisers/cuppa.jpg
  video: http://player.vimeo.com/video/74912287
  title: Cuppa
- image: /img/amagi/advertisers/bluestone.png
  video: http://player.vimeo.com/video/74912281
  title: Bluestone
- image: /img/amagi/advertisers/canarylondon.jpg
  video: http://player.vimeo.com/video/74912285
  title: Canary London
---
<div class="main-content">
  <div class="clearfix">
    <h1>Advertisers</h1>

    <h2>Our Clients</h2>

    <p>Take a look at our proud clients.<b>Click on logos to view ads</b> </p>

    <div>
      {% for c in page.clients %}
      <div style="text-align:center;float:left;width:200px;height:200px;line-height:200px;">
        <a href="{{c.video}}" data-fancybox-type="iframe" data-fancybox-height="480" class="fancybox fancybox.iframe" title="{{c.title}}" style="">
          <img style="max-width:120px;max-height:120px;" src="{{c.image}}" alt="{{c.title}}" />
        </a>
        <!--<div class="mosaic-backdrop"><img src="{{c.image}}" alt="{{c.title}}" /></div>-->
      </div>
      {% endfor %}
    </div>


  </div>
</div>


