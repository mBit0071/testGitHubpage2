---
title: DD
layout: page
---


Some stuff here.

{% for category in site.categories %}

{% if category[0] contains page.title %}
{% for ps in category[1] %}
1. [{{ps.title}}]({{site.baseurl}}{{ps.url}}) 
{% endfor %}
{% endif %}
 
{% endfor %}

