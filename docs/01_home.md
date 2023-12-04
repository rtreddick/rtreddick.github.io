---
layout: home
title: Home
nav_order: 1
description: "Home"
permalink: /
---

![](./assets/images/tim-reddick-logo.png)

---

{: .highlight-title }
> Work in progress
>
> Welcome! This site is built and deployed using Jekyll, GitHub Actions, and GitHub Pages. I'm still gathering content to make it feel complete, but I'd thought I'd publish now and share my progress. No time like the present! The [git repo](https://github.com/rtreddick/rtreddick.github.io) for this site is public, so take a look if you're interested.

---

<ul>
  {% for post in site.posts %}
  <li>
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <h4>{{ post.date | date_to_string }} - Tim Reddick</h4>
    {{ post.excerpt }}
  </li>
  {% endfor %}
</ul>