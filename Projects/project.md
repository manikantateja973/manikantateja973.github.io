---
title: My Projects
description: Collection of technical implementations
---

## Featured Projects

{% raw %}{% for project in site.projects limit:3 %}
<div class="project-card">
  <h3>{{ HeirGym }}</h3>
  <p>{{ RA Project}}</p>
  <a href="{{ https://github.com/grc-iit/HeirGym/tree/master/heirgym
 }}">View Details</a>
</div>
{% endfor %}{% endraw %}

