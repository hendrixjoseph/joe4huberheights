---
title: Huber Heights City Council Actions
---

Since February 2021, summaries of city council actions, in PDF form, have been available on [Huber Heights website](https://www.hhoh.org/549/City-Council-Actions). However, only the past two or so for both *City Council Work Sessions* and *City Council Meetings* are available.

My goal for this page is to archive all the past summary PDF files so anyone can easily access them.

## City Council Work Sessions

{% assign work_sessions = site.static_files | where_exp: "file", "file.path contains 'city-council-work-sessions'" | reverse %}
{% for file in work_sessions %}
* [{{ file.basename  | date: "%B %d, %Y" }}]({{ file.path }}){% endfor %}

## City Council Meetings

{% assign council_meetings = site.static_files | where_exp: "file", "file.path contains 'city-council-meetings'" | reverse %}
{% for file in council_meetings %}
* [{{ file.basename  | date: "%B %d, %Y" }}]({{ file.path }}){% endfor %}