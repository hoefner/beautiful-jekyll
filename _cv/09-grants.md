---
slug: cv-grants
title: Grants &amp; Funding
nav: Grants
order: 9
---

{% assign end_years = site.grants | map: 'end' | uniq | sort | reverse %}
{% for year in end_years %}{% assign year_bucket = site.grants | where: 'end', year %}{% assign start_years = year_bucket | map: 'start' | uniq | sort | reverse %}{% for syear in start_years %}{% assign inner = year_bucket | where: 'start', syear | sort: 'title' | reverse %}{% for g in inner %}
<div class="grant-item">
<div class="grant-title">{{ g.title }}</div>
<div class="grant-meta">{{ g.funder }}{% if g.amount %} &nbsp;·&nbsp; {{ g.amount }}{% endif %}{% if g.role %} &nbsp;·&nbsp; {{ g.role }}{% endif %}{% if g.years %} &nbsp;·&nbsp; {{ g.years }}{% elsif g.start and g.end and g.start != g.end %} &nbsp;·&nbsp; {{ g.start }}–{{ g.end }}{% elsif g.start %} &nbsp;·&nbsp; {{ g.start }}{% endif %}{% if g.note %} &nbsp;·&nbsp; <em>{{ g.note }}</em>{% endif %}</div>
</div>
{% endfor %}{% endfor %}{% endfor %}
