---
layout: archive
title: Projects
permalink: /projects/
author_profile: true
---


{% for project in site.projects %}
{% if project.root %}
<h2><a href="{{ project.permalink | prepend: site.baseurl }}">
   {{ project.title }}
</a></h2>

<p class="post-excerpt">{{ project.description | truncate: 160 }}</p>
{% endif %}
{% endfor %}