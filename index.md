---
layout: default
---

### [Click here for the full project description]({{ site.baseurl }}{% link about.md %})
### [Mid-semester project update](http://tammydoestheneedful.com/ctci/2023/07/13/heaps3.html#mid-semester-project-update)
### Reflections are at the end of each weekly check-in, but if you are just looking for the reflections and not the check-ins, [Click here for a list with links to each reflection]({{ site.baseurl }}{% link reflections-list.md %})

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
