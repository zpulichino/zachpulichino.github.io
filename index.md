---
title: "Zach Pulichino – Deal Sourcing Portfolio"
theme: minima
---

# Deal Sourcing Portfolio
A selection of my AI infrastructure & vertical SaaS memos.

{% for file in site.static_files %}
{% if file.path contains 'memos/' %}
- [{{ file.name | remove: '.pdf' }}]({{ file.path }})
{% endif %}
{% endfor %}
