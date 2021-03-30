---
title: Expenses
---

date | amount | where | what
--- | --- | --- | ---
{% for expense in site.data.expenses %}{{ expense.date }} | {{ expense.amount }} | {{ expense.where }} | {{ expense.what }}
{% endfor %}
