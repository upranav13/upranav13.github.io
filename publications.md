---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
classes: wide
---

{% assign pubs = site.data.publications | sort: "Year" | reverse %}
{% assign grouped = pubs | group_by: "Year" %}

{% for g in grouped %}
## {{ g.name }}

<div class="pubs-grid">
  {% for p in g.items %}
  <article class="pub-card">
    {% if p.thumbnail %}
    <a href="{{ p.pdf | default: p.doi | default: '#' }}">
      <img class="pub-thumb" src="{{ p.thumbnail | relative_url }}" alt="thumbnail for {{ p.Title }}">
    </a>
    {% endif %}

    <div class="pub-meta">
      <h3 class="pub-title">{{ p.Title }}</h3>
      <p class="pub-authors">{{ p.Authors }}</p>
      {% if p["Journal name"] %}
      <p class="pub-venue"><em>{{ p["Journal name"] }}</em></p>
      {% endif %}

      <p class="pub-links">
        {% if p.doi %}<a class="btn btn--small" href="{{ p.doi }}">DOI</a>{% endif %}
        {% if p.pdf %}<a class="btn btn--primary btn--small" href="{{ p.pdf | relative_url }}">PDF</a>{% endif %}
      </p>
    </div>
  </article>
  {% endfor %}
</div>

<hr>
{% endfor %}
