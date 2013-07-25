---
layout: page
title: dose.io
tagline: slow-drip poetics
---
{% include JB/setup %}

Flash fiction, poetry, commentary, propaganda
    
## Preliminary Posts

Some poems written as part of a [git centered poetry project](https://github.com/mturro/poem "Poem"):

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This site is evolving. It is equal parts technical playground and creative outlet. If you find yourself here you are welcome to periodically check back and monitor any progress that might be made… if that kind of thing appeals to you.


