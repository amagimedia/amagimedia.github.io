---
layout: default
title: advertisers
navigation: advertisers
hulbrands:
- image: /img/amagi/advertisers/vim.jpg
  video: http://player.vimeo.com/video/75466489
  title: VIM Double Dhamaka
- image: /img/amagi/advertisers/tresemme.jpg
  video: http://player.vimeo.com/video/75466488
  title: TRESemme Diana Satchet
- image: /img/amagi/advertisers/pepsodent.jpg
  video: http://player.vimeo.com/video/75466483
  title: Pepsodent Toothpaste
- image: /img/amagi/advertisers/pureit.jpg
  video: http://player.vimeo.com/video/75466480
  title: PureIT Water Purifier
- image: /img/amagi/advertisers/pears.jpg
  video: http://player.vimeo.com/video/75466478
  title: Pears Soap
- image: /img/amagi/advertisers/lifebuoy.jpg
  video: http://player.vimeo.com/video/75466477
  title: LifeBuoy Soap
- image: /img/amagi/advertisers/knorr.png
  video: http://player.vimeo.com/video/75466476
  title: Knorr Soup
- image: /img/amagi/advertisers/kissan.jpg
  video: http://player.vimeo.com/video/75466475
  title: Kissan Tomato Ketchup
- image: /img/amagi/advertisers/huggies.jpg
  video: http://player.vimeo.com/video/75466473
  title: Huggies Wonder Pants
- image: /img/amagi/advertisers/domex.jpg
  video: http://player.vimeo.com/video/75466466
  title: Domex
clients:
- image: /img/amagi/advertisers/hcl.png
  video: http://player.vimeo.com/video/74912298
  title: HCL Computers
- image: /img/amagi/advertisers/lenskart.png
  video: http://player.vimeo.com/video/74912304
  title: Lenskart
- image: /img/amagi/advertisers/bluestone.png
  video: http://player.vimeo.com/video/74912281
  title: Bluestone
- image: /img/amagi/advertisers/yepme.png
  video: http://player.vimeo.com/video/74912309
  title: Yepme
- image: /img/amagi/advertisers/dpauls.png
  video: http://player.vimeo.com/video/74912289
  title: DPauls
- image: /img/amagi/advertisers/bikaji.jpg
  video: http://player.vimeo.com/video/74912280
  title: Bikaji
- image: /img/amagi/advertisers/arena.png
  video: http://player.vimeo.com/video/74912278
  title: Arena Multimedia
- image: /img/amagi/advertisers/arena.png
  video: http://player.vimeo.com/video/74912308
  title: Raag Vanaspati
- image: /img/amagi/advertisers/kidzee.png
  video: http://player.vimeo.com/video/74912302
  title: Kidzee
- image: /img/amagi/advertisers/honda.jpg
  video: http://player.vimeo.com/video/74912301
  title: Honda Motors
- image: /img/amagi/advertisers/carbon.jpg
  video: http://player.vimeo.com/video/74912294
  title: Forever Diamonds
- image: /img/amagi/advertisers/finolex.jpg
  video: http://player.vimeo.com/video/74912292
  title: Finolex
- image: /img/amagi/advertisers/cuppa.jpg
  video: http://player.vimeo.com/video/74912287
  title: Cuppa
- image: /img/amagi/advertisers/canarylondon.jpg
  video: http://player.vimeo.com/video/74912285
  title: Canary London
---
<div class="main-content">
  <div class="clearfix">
    <h1>Advertisers</h1>

    <p>Amagi hosts wide range of customers from small &amp; medium business to large national advertisers. Take a look at some of the adverisers using Amagi's platform.
    <p><b>Click on logos to view ads</b> </p>

    <h2>HUL Brands</h2>
    <div class="clearfix">
      {% for c in page.hulbrands %}
      <div style="text-align:center;float:left;width:200px;height:200px;line-height:200px;">
        <a href="{{c.video}}" data-fancybox-type="iframe" data-fancybox-height="480" class="fancybox fancybox.iframe" title="{{c.title}}" style="">
          <img style="max-width:120px;max-height:120px;" src="{{c.image}}" alt="{{c.title}}" />
        </a>
      </div>
      {% endfor %}
    </div>

    <h2>Other Advertisers</h2>
    <div class="clearfix">
      {% for c in page.clients %}
      <div style="text-align:center;float:left;width:200px;height:200px;line-height:200px;">
        <a href="{{c.video}}" data-fancybox-type="iframe" data-fancybox-height="480" class="fancybox fancybox.iframe" title="{{c.title}}" style="">
          <img style="max-width:120px;max-height:120px;" src="{{c.image}}" alt="{{c.title}}" />
        </a>
      </div>
      {% endfor %}
    </div>

  </div>
</div>


