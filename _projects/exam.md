---
layout: archive
title: Exam system
permalink: /projects/exam/
author_profile: true
---


{% for project in site.projects %}
<h2><a href="{{ project.link | prepend: site.baseurl }}">
   {{ project.title }}
</a></h2>

<p class="post-excerpt">{{ project.description | truncate: 160 }}</p>
{% endfor %}