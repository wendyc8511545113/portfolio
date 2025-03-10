---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: false
---

A complete list of pages available on this site. An [XML version]({{ "sitemap.xml" | relative_url }}) is also available for search engines.

## **Main Pages**
- [Home]({{ "/" | relative_url }})
- [About]({{ "/about/" | relative_url }})
- [Projects]({{ "/projects/" | relative_url }})
- [Resume]({{ "/resume/" | relative_url }})

{% if site.collections.size > 0 %}
## **Portfolio Sections**
{% for collection in site.collections %}
{% unless collection.output == false %}
  - **{{ collection.label | capitalize }}**
  {% for doc in collection.docs %}
    - [{{ doc.title }}]({{ doc.url | relative_url }})
  {% endfor %}
{% endunless %}
{% endfor %}
{% endif %}
