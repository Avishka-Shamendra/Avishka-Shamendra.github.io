---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


<!-- {% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %} -->

{% include base_path %}

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

{% for post in site.publications reversed %}
## [{{ post.title }}]({{ post.permalink }})
{{ post.citation }}<br>
_{{ post.venue }}_

{{ post.excerpt }}

[Download Paper]({{ post.paperurl }})

{% endfor %}