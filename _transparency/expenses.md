---
title: Expenses & Contributions
---

These "expenses" will be reported as "in-kind" contributions to my campaign (or, more accurately, to my committee *Citizens for Joseph Hendrix*) on [Form 31-J-1](https://www.sos.state.oh.us/globalassets/candidates/forms/31j1.pdf). They are all paid by me, out of my own pocket.

In addition to the details in the table below, the form requires me to list myself as a contributor, including my name (Joseph Hendrix), my address (6019 Taylorsville Rd), and my employer (Northrop Grumman).

date | amount | where | what
---: | ---: | --- | ---
{% assign total = 0 %}{% for expense in site.data.expenses %}{{ expense.date }} | {{ expense.amount }} | {{ expense.where }} | {{ expense.what }}{% capture cost %}{{ expense.amount | remove: "$" }}{% endcapture %}{% assign total_expenses = total_expenses | plus: cost %}
{% endfor %} | **${{ total_expenses }}** | |

I've also had a couple of in-kind contributions, both for my [April 10th Community Cleanup](/huber-heights-community-cleanup/):

date | amount | who | what
---: | ---: | --- | ---
{% assign total = 0 %}{% for contribution in site.data.contributions %}{{ contribution.date }} | {{ contribution.amount }} | {{ contribution.who }} | {{ contribution.what }}{% capture cost %}{{ contribution.amount | remove: "$" }}{% endcapture %}{% assign total_contributions = total_contributions | plus: cost %}
{% endfor %} | **${{ total_contributions }}** | |

All together, that means {% assign total = total | plus: total_expenses | plus: total_contributions %}**${{ total }}** has been spent on my campaign.

## Pre-Primary Campaign Finance Report

The pre-primary campaign report contains all contributions and expenses up to April 14th, 2021. Hence, contributions and expenses after that date are not on it.

The report was due April 22nd, 2021 by 4pm, but I submitted it a couple of days early on April 19th. There is a post-primary campaign finance report that is due June 11th at 4pm.

{% include pdf.html src="/pdf/pre-primary-campaign-finance-report.pdf" %}

## Post-Primary Campaign Finance Report

The post-primary campaign report contains all contributions and expenses, including those that were reported on the pre-primary campaign report.

The report was due June 11th, 2021 by 4pm, but I submitted it a couple of weeks early on May 25th. I would have submitted it earlier, but I was waiting for a Facebook Ad bill to be paid (it was paid on May 23rd).

{% include pdf.html src="/pdf/post-primary-campaign-finance-report.pdf" %}