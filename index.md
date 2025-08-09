---
layout: home
title: "Welcome"
---

# Sagnik Majumder
_Physics · Astroparticle · Research notes_

 The sky has always made people wonder about strange things—where do we truly belong, what is our purpose ? how small are we ? and where does the sky end ? As a child, I would lie on the rooftop of my home and gaze at the sky for hours. These same questions wandered through my mind. I remember watching ``Through the Wormhole with Morgan Freeman'' on the Discovery Channel—he often explored these very questions. That genuinely amazed and curious child chose the journey of physics to quench his thirst, only to realise, moments later in life, that years had passed and he was buried under assignments and deadlines. Crawling back up, he tries to look at the sky again—and it amazes him, just as it did years ago.
 
So, he decides to create a diary—a space to share that amazement. And thus, welcome to the blog!

---

## Featured
{% if site.posts.size > 0 %}
### {{ site.posts.first.title }}
{{ site.posts.first.excerpt | strip_html | truncate: 200 }}
[Read more]({{ site.posts.first.url }})
{% endif %}

---

## Recent posts
<ul>
  {% for post in site.posts limit:6 %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%b %-d, %Y" }}</small><br>
    <small>{{ post.excerpt | strip_html | truncate: 140 }}</small>
  </li>
  {% endfor %}
</ul>

---

## About
I am a PhD student at IISER Mohali. [More →](/about)



## Blog Posts

- [My First Post](blog1.md)
- [GRBs and Supernovae](grb-supernova.md)
