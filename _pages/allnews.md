---
title: "News"
layout: textlay
excerpt: "Marconi Society Machine Learning Laboratory, Makerere University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
