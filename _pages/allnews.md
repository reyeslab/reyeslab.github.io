---
title: "News"
layout: textlay
excerpt: "Reyes Biophysics Lab at CINVESTAV."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
