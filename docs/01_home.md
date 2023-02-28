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
> Welcome! This is one of my first attempts at building and deploying a website using Jekyll, GitHub Actions, and GitHub Pages. I'm still gathering and building up the content to make this site feel complete, but I'd thought I'd publish now and share my progress. No time like the present! The [git repo](https://github.com/rtreddick/rtreddick.github.io) for this site is public, so take a look if you're interested. The layout of the site may change as I figure out how to best arrange the content. Thanks for visiting!

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