---
layout: default
title: Hobbies
nav_order: 6
description: "An introduction to some of my hobbies and interests."
permalink: /hobbies
---

# Hobbies
{: .fs-9}

I've had several hobbies and interests over the years. Here are a few highlights.
{: .fs-6 .fw-300 }

---

{% for hobby in site.hobbies %}
  <h3><a href="{{ hobby.url }}">{{ hobby.hobby }}</a></h3>
  ![]({{ hobby.key-photo }})
{% endfor %}

---