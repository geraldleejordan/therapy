---
layout: page
title: Chapters
---

<h2>Before You Begin</h2>

 <ul>
 {% assign sorted_posts = (site.categories.['chapters-beginning'] | sort: 'title') %}
{% for post in sorted_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

<h2>Theory</h2>

 <ul>
 {% assign sorted_posts = (site.categories.['chapters-theory'] | sort: 'title') %}
{% for post in sorted_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

<h2>Practice</h2>

 <ul>
 {% assign sorted_posts = (site.categories.['chapters-practice'] | sort: 'title') %}
{% for post in sorted_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

<h2>Reflection</h2>