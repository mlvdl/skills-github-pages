---
title: This is a blog
my_plot: interactive_rates.html
---

# Welcome to My GitHub Page

This is a simple webpage using Markdown.

## Embedded Plotly Chart

[Click here to view my Plotly chart](interactive_rates.html)

{% if page.my_plot %}
  {% include {{ page.my_plot }} %}
{% endif %}
