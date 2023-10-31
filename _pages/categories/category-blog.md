---
title: "blog"
permalink: categories/blog/
layout: category
author_profile: true
taxonomy: blog
---

Blog 카테고리의 글들입니다.

{% assign posts = site.categories.Blog %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}