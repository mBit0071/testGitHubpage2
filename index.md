---
title: My page
layout: default
---

# {{ page.title }}

The following is converted from md to HTML. 

Content is written in [Markdown](https://learnxinyminutes.com/docs/markdown/).
Plain text format allows you to focus on your **content**.

## Links

### Page links

{% for ps in site.categories %}
1. [{{ps | first | strip_html}}]({{site.baseurl}}{{ps | first | strip_html}})
{% endfor %}


