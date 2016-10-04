---
layout: archive
title: Exam system
permalink: /projects/exam/
author_profile: true
---


{% for item in site.projects.exam %}
<a href="{{ item.link | prepend: site.baseurl }}">
   {{ item.title }}
</a>

<p class="post-excerpt">{{ item.description | truncate: 160 }}</p>
{% endfor %}