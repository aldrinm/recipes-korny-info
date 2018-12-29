---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Recipes
list_title: Blog posts
---

{% assign sorted = site.recipes | sort:"date" %}
{% for post in sorted %}
  * [{{post.title}}]({{ post.url | prepend: site.baseurl }})
{% endfor %}

## [Recipes by tag](tag)
