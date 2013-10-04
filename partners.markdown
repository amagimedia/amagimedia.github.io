---
layout: default
title: Partners
navigation: partners
items:
- name: Zee TV
  image: /img/amagi/partners/partners_zee_tv.jpg
  description: Zee TV, the flagship channel of Zee Entertainment Enterprises LTD was launched in October 1992.  Nearly two decades since its launch, Zee TV has driven the growth of the satellite and cable industry in India. The popularity of Zee arises from its understanding of Indian culture and beliefs which are depicted in its programming.
- name: Zee News
  image: /img/amagi/partners/zee-news.png
  description: Zee News, is an Indian news and current affairs channel founded in 1999. Zee News is a part of Zee News Ltd (ZNL), which is itself a part of Essel Group.
- name: Zee Business
  image: /img/amagi/partners/zee-business.png
  description: Zee Business is a Hindi business news channel based in Mumbai, India. Their tagline "Money Matters Simplified" is a reflection of their content approach to business news. 
- name: Ten Sports
  image: /img/amagi/partners/tensports_logo.jpg
  description:   TEN Sports is an Indian sports channel owned and operated by Zee Network. Ten Sports own long term broadcast rights for five cricket boards - South Africa,West Indies, Zimbabwe, Pakistan and Sri Lanka, offering its viewers the best of sports action round the clock. TEN Sports was launched on April 1, 2002, and became the premier sports channel for South Asians. 
- name: Times Now
  image: /img/amagi/partners/partners_14.png
  description:  TIMES NOW is a Leading 24-hour English News channel that provides the Urbane viewers the complete picture of the news that is relevant, presented in a vivid and insightful manner, which enables them to widen their horizons & stay ahead. Arnab Goswami is the Editor-in Chief and a hosts the fiery news hour , one of the most watched news shows in the country. TIMES NOW is brought to you by Times Global Broadcasting Co. Ltd., a Bennett, Coleman & Co service.
- name: CNBC Awaaz
  image: /img/amagi/partners/partners_13.png
  description: CNBC Awaaz is a business news TV channel in India. The channel is a joint venture between CNBC and Television Eighteen India Limited (TV18) based in Mumbai. The CNBC AWAAZ editorial team brings with them more than 15 years of experience each and a nationwide network spanning more than 45 cities. The Network18 Group is a media and entertainment company with interests in television, internet, films, digital commerce, magazines, mobile content and allied businesses.
- name: IBN 7
  image: /img/amagi/partners/p2.png
  description: IBN7 (Indian Broadcast Network) is a Hindi news television channel owned by Network 18 Ltd based in Mumbai. Ashutosh, the Managing Editor of the channel. IBN7 has launched several initiatives like IBN7 Diamond States Awards, IBN7 Super Idols, Zindagi LIVE Awards, Citizen Journalist Awards, Young Indian Leaders, Guru Shishya Awards etc.
- name: CNN IBN
  image: /img/amagi/partners/cnn_ibn_tv.png
  description:  CNN-IBN is a partnership between Global Broadcast News (GBN), a Network18 Company, and Turner International (Turner) in India. Rajdeep Sardesai is the Editor-in-Chief, his flagship show on CNN-IBN, India at 9, was awarded the Best News Show at the Asian Television Awards, 2010. The 24-hour, English-language news channel is spearheaded by renowned television journalist Rajdeep Sardesai as the Editor-in-Chief. 
- name: UTV Movies
  image: /img/amagi/partners/partners_09.png
  description: UTV Movies is a Hindi movie channel in India based in Mumbai, Maharashtra and is owned by UTV. It airs blockbuster Bollywood films from UTV's own library as well as other major movie studios in India. 
- name: Zoom
  image: /img/amagi/partners/partner_page_logo_22.png
  description: Zoom is part of Bennett, Coleman &amp; Co. Limited, India's most respected media conglomerate – The Times Group. The 168-year-old group is a market driver across all media platforms including media brands like The Times Of India, The Economic Times, Radio Mirchi, Times Now , ET Now and Femina.
---
<div class="main-content">
  <div class="clearfix partners">
    <h1>Partnering for success</h1>
    <p>amagi partners with TV networks, cable operators and DTH operators to enable Targeted TV advertising. </p>

    <h2>Our Broadcast Partners</h2>

    {% for c in page.items %}
    <div class="item clearfix">
      <div class="fourth">
        <img src="{{c.image}}" alt="{{c.name}}" />
      </div>

      <div class="three-fourths last">{{c.description}}</div>
    </div>
    {% endfor %}

    <hr/>
    <h2>Our DTH Partner</h2>
    <div class="item clearfix">
      <div class="fourth">
        <img src="/img/amagi/partners/Tata-Sky-Logo-2D.png" alt="Tata Sky" />
      </div>

      <div class="three-fourths last">
        TATA Sky is a direct broadcast satellite television provider in India. Incorporated in 2004, Tata Sky is a JV between the TATA Group and STAR. It currently offers close to 196 channels (as of December 2010).
      </div>
    </div>

  </div>
</div>

