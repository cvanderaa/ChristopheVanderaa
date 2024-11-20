---
layout: archive
permalink: /blog/
title: "Blog"
---



{% include group-by-array collection=site.posts field="tags" %}

{% for tag in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ tag | slugify }}" class="archive__subtitle">{{ tag }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}

{% for post in site.posts %}
  {% if post.tags contains "lifestyle" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
