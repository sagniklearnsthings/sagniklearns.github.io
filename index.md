---
layout: home
title: "Welcome"
---

# Why this page ?
_about anything logical_

 The sky has always made people wonder about strange things—where do we truly belong? what is our purpose ? how small are we ? and where does the sky end ? As a child, I would lie on the rooftop of my home and gaze at the sky for hours. These same questions wandered through my mind. I remember watching ``Through the Wormhole with Morgan Freeman'' on the Discovery Channel—he often explored these very questions. That genuinely amazed and curious child chose the journey of physics to quench his thirst, only to realise, moments later in life, that years had passed and he was buried under assignments and deadlines. Crawling back up, he tries to look at the sky again—and it amazes him, just as it did years ago.
 
So, he decides to create a diary—a space to share that amazement. And thus, welcome to the blog!

---

## Recent Posts
<ul>
  {% assign sorted_posts = site.posts | sort: 'date' | reverse %}
  {% for post in sorted_posts limit:6 %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%b %-d, %Y" }}</small><br>
    <small>{{ post.excerpt | strip_html | truncate: 140 }}</small>
  </li>
  {% endfor %}
</ul>

---

## Blog Posts
<ul>
  {% assign sorted_posts = site.posts | sort: 'date' | reverse %}
  {% for post in sorted_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%b %-d, %Y" }}</small>
  </li>
  {% endfor %}
</ul>

---

## About
Know about me ? Click here ---> [More →](blog1.md)



