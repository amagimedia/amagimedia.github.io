---
layout: default
navigation: press
title: Amagi Media Labs Press Release
press: 
- date: 07 Sep, 2013
  title: Zee, Amagi in geo-targeting tie-up
  summary: Ad networking company Amagi and Zee Entertainment Enterprises have partnered to bring ‘geo-targeting’ on the latter’s general entertainment channel, Zee TV. Geo-targeting allows advertisers to target specific geographies on national TV channels. Amagi provides geo-targeting solutions for over 15 channels spanning news, movies, sports, music and lifestyle. A press release from Amagi, quoting Ashish Sehgal, Chief Sales Officer, Zee TV, says "Thanks to the Amagi tie-up, Zee can now make available a whole new set of targeting options for advertisers. Zee TV is also looking to increase its client base through geo targeting, which will help local clients target their specific markets on a large GEC."
  href: http://www.thehindubusinessline.com/companies/zee-amagi-in-geotargeting-tieup/article5104488.ece
  source: Hindu BusinessLine
  source_url: http://www.thehindubusinessline.com
- date: 22 Aug, 2013
  title: Amagi to geo-target HUL ads on Nickelodeon
  summary: Amagi Media, Hindustan Unilever (HUL) and Viacom18 have struck a deal which will enable HUL to get geo-targeted advertising on Nickelodeon. Given TRAI's recent 12-minute ruling on advertising, broadcasters and advertisers have been seeking ways to optimise their return on investment and stretch the time within the limited inventory, and this is a step towards it.
  href: http://www.afaqs.com/news/story/38448_Amagi-to-geo-target-HUL-ads-on-Nickelodeon
  source: afaqs.com
  source_url: http://afaqs.com
- date: 26 Jul, 2013
  title: Amagi is redefining television advertising
  summary: In his attempt to change the television viewing experience, Srinivasan, Vidhya Srinivasan and Baskar Subramanian, co-founders of Amagi, have developed a technology platform for customizing television (TV) advertisements. This is something akin to what Google did to online advertising with Google Adwords.
  href: http://entrepreneurindia.in/start-ups/amagi-is-redefining-television-advertising/20972/
  source: entrepreneurindia
  source_url: http://entrepreneurindia.in
- date: 25 May, 2012
  title: Multiply TV ad inventory
  summary: Only thing that is constant in the TV land today is change. In the next few years, the TV industry of India will look far different from what it is today.  The big drivers for this change are digitisation drive by the government, ushering in of HD channels and rationalisation in terms of advertising and content time that is being driven by TRAI.
  href: http://www.exchange4media.com/46498_multiply-tv-ad-inventory.html
  source: Exchange4media
  source_url: http://www.exchange4media.com/
- date: 27 Mar, 2012
  title: Amagi's New Trick for Broadcast Advertising
  summary: Soon, while you are watching a show on national television, you might find yourself watching an advert for the mom-and-pop store down your road. In fact, even today while watching some channels, you might be watching advertising that is being aired only in your city. At the same time, your friend in another city who is watching the same show could be watching a different ad. The company behind this technology is the relatively unknown Bangalore-headquartered Amagi Media Labs. This four-year-old company is gradually disrupting the conventional wisdom and business model around TV advertising in India. 
  href: http://forbesindia.com/printcontent/32588
  source: ForbesIndia
  source_url: http://forbesindia.com
---
	
<div class="main-content">
  {% for item in page.press %}
  <!-- Start Post --> 
  <div class="clearfix">
    <h1 class="four-fifths right last"><a target="_blank" href="{{item.href}}">{{item.title}}</a></h1>
    <!-- Start Meta -->
    <aside class="left-aside left fifth">
    <ul class="meta">
      <li>{{item.date}}</li>
      <li><a target="_blank" href="{{item.source_url}}">{{item.source}}</a></li>
    </ul>	
    </aside> 
    <div class="four-fifths right last">

      <p>{{item.summary}}</p>
      <p><a class="btn" target="_blank" href="{{item.href}}">Read More</a></p>
    </div>
  </div>

  <hr/>
  {% endfor %}

</div>
