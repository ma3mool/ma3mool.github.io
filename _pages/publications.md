---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Color code: <strong><font color="green">Green</font></strong>: conference, <strong><font color="orange">Orange</font></strong>: journal, <strong><font color="purple">Purple</font></strong>: workshop.

[comment]: <> ({% if author.googlescholar %})
You can also find my articles on <a href="https://scholar.google.com/citations?user=LRZKQpkAAAAJ&hl=en">my Google Scholar profile</a>.

{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
