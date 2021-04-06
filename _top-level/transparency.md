---
title: Campaign Transparency Portal
layout: template
---

## Facebook Ad Library

To see what ads I've ran (or am running) on Facebook, check out my [campaign page's entry in the Facebook Ad Library](https://www.facebook.com/ads/library/?id=1619605648232044).

I do not use "Facebook Pixel" to track on this website. However, if you come here via Facebook, Facebook will add an "fbclid" parameter into the URL. I don't use this information, but other sites that you visit from Facebook may.

## Google Programs

### Google Analytics

I use Google Analytics to determine site traffic, sources of said traffic, and user behavior. Neither I nor this site will attempt to identify you personally using Google Analytics.

If you wish to know more or even opt out, view [Google's privacy policy](http://www.google.com/intl/en/policies/privacy/).

### Google Search Console

I use Google Search Console to see what people searched for to get to this site, what page they ended up visiting. Google Search Console also tells me what country the person who searched for my site is from, what device (mobile, desktop, tablet, etc.) they are using, and the date they searched.

## Other Pages in the Transparency Portal:

{% for post in site.transparency %}
* [{{ post.title }}]({{ post.url }}){% endfor %}