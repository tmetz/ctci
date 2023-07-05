---
layout: default
---

## [Click here for the full project description]({{ site.baseurl }}{% link about.md %})
## Reflections are at the end of each weekly check-in, but if you are just looking for the reflections and not the check-ins, [Click here for a list with links to each reflection]({{ site.baseurl }}{% link reflections-list.md %})

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
