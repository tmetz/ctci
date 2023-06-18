---
layout: default
---

## [Click here for the full project description]({{ site.baseurl }}{% link about.md %})

<ul>
  {% for post in site.posts %}
    <li>
      ## <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
