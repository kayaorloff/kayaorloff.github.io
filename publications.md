---
title: "Publications"
permalink: /publications/
layout: default
---

<p>Total publications: {{ site.publications | size }}</p>

<ul>
{% for pub in site.publications %}
  <li>
    <strong>{{ pub.title }}</strong>
  </li>
{% endfor %}
</ul>
