---
title: "News | Language and Data Intelligence Lab"
layout: textlay
excerpt: "News | Language and Data Intelligence Lab"
sitemap: false
permalink: /allnews.html
---
{% for article in site.data.news %}

<p>{{ article.date }} <br>
{% endfor %}
