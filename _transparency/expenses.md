---
title: Expenses
---

These "expenses" will be reported as "in-kind" contributions to my campaign (or, more accurately, to my committee *Citizens for Joseph Hendrix*) on [Form 31-J-1](https://www.sos.state.oh.us/globalassets/candidates/forms/31j1.pdf). They are all paid by me, out of my own pocket.

In addition to the details in the table below, the form requires me to list myself as a contributor, including my name (Joseph Hendrix), my address (6019 Taylorsville Rd), and my employer (Northrop Grumman).

date | amount | where | what
--- | --- | --- | ---
{% for expense in site.data.expenses %}{{ expense.date }} | {{ expense.amount }} | {{ expense.where }} | {{ expense.what }}
{% endfor %}
