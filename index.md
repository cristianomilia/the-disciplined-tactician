---
layout: default
title: The Disciplined Tactician.
---

# Header 1

Content.

## Header 1.1

Other content.

# Header 2

Yet another bit of content.

And yet more.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>