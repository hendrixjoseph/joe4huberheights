---
layout: post
title: Introducing the Joseph Hendrix Huber Heights Ward 3 Campaign Transparency Portal
---

How can I claim I will make Huber Heights City Government more transparent if my campaign isn't transparent?

That's why I'm creating a transparency portal on this website. So far I've got two sections based on two different types of reporting I'm required to do with Ohio: a [Financial Disclosure section](/financial-disclosure-statement/) based on the Ohio Ethics Commission Financial Disclosure Statement I was required to file, and an [expenses section](/expenses/) based on the campaign finance reports I will be required to file.

The website sections are better organized than the paperwork I'm required to file. Plus I am going to include the paperwork (in PDF form) embedded on those pages, as well. I've already embedded the Ohio Ethics Commission Financial Disclosure Statement in the Financial Disclosure section.

As I add more sections, I'll include them in the following list:

{% for post in site.transparency %}
* [{{ post.title }}]({{ post.url }}){% endfor %}