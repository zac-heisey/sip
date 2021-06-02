---
layout: layouts/blocks.njk
title: SIP Sitemap
description:
blocks:
- template: body-content
  type: body-content
eleventyExcludeFromCollections: true
---

## Pages

{% for page in collections.all %}

  {# Remove posts for collections.all #}
  {% if not page.data.tags %}

  [{{ page.data.title }}]({{ page.url }})

  {% endif %}

{% endfor %}

---

## Posts

{% for post in collections.posts %}

  [{{ post.data.title }}]({{ post.url }})

{% endfor %}
