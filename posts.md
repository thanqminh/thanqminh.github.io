---
layout: archive
title: Posts
permalink: /posts/
author_profile: true
---


{% for post in site.posts %}

<h2><a href="{{ post.permalink | prepend: site.baseurl }}">
   {{ post.title }}
</a></h2>

{% if post.excerpt %}<p class="archive__item-excerpt" itemprop="description">{{ post.excerpt | markdownify | strip_html | truncate: 160 }}</p>{% endif %}

{% endfor %}