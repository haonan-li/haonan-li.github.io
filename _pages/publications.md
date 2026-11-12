---
title: "Publications"
permalink: /publications/
layout: clean
---
<p class="note">* Equal contribution. Long author lists are abbreviated. A complete, up-to-date list is on <a href="{{ site.author.googlescholar }}">Google Scholar</a>.</p>

{% assign years = site.data.publications | group_by: "year" | sort: "name" | reverse -%}
{%- for y in years %}
<h2>{{ y.name }}</h2>
{% for pub in y.items %}{% include pub.html pub=pub %}{% endfor %}
{%- endfor %}
