---
title: "News"
layout: textlay
excerpt: "Microstructure and Plasticity"
sitemap: false
permalink: /allnews.html
---

# News
---

{% for article in site.data.news %}
{{ article.date }}
{{ article.headline | markdownify}}
<br/>

---

{% endfor %}
