---
title: "Publications | Language and Data Intelligence Lab"
layout: gridlay
excerpt: "Publications | Language and Data Intelligence Lab"
sitemap: false
permalink: /publications/
---




# Publications

{% for publi in site.data.publist.publications %}
**{{ publi.title }}**  
<em>{{ publi.authors }}</em>  
{{ publi.venue }} ({{ publi.year }})

---
{% endfor %}
