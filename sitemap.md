---
layout: layouts/base.njk
title: SIP Sitemap
description:
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

{% for post in collections.posts | reverse %}

  [{{ post.data.title }}]({{ post.url }})

{% endfor %}
