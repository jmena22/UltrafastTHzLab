---
title: "News"
layout: textlay
excerpt: "Ménard Lab at uOttawa."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br> {{ article.headline | markdownify}}</p>
{% endfor %}
