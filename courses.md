---
layout: archive
title: Courses
permalink: /courses/
author_profile: true
---


{% for course in site.courses %}

<a href="{{ course.url | prepend: site.baseurl }}">
   {{ course.title }}
</a>
{% endfor %}