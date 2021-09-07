---
layout: page
title:  "Personal Projects"
---

Although I develop software full time, my main hobby is _even more development_. I always have at least 1 random
game dev idea that I'm working on, without any particular end goal in mind. Often these projects serve to try
something out - a new concept, technology, framework, gameplay mechanic idea, and so on.

---

Here I will try to list and showcase some of my recent efforts to realize some ideas.


{% assign doclist = site.data.projects.docs | sort: 'title'  %}
<ol>
{% for item in doclist %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
{% endfor %}
</ol>
