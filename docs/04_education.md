---
layout: default
title: Education
nav_order: 4
description: "An overview of my education and some classes I've taken"
permalink: /education
---

# Education
{: .fs-9}

I learn every day through books, podcasts, and online courses. Here I highlight my degrees and some of my continuing education experiences.
{: .fs-6 .fw-300 }

---

{% for degree in site.degrees %}
  <h3><a href="{{ degree.url }}">{{ degree.degree }}</a></h3>
  {{ degree.institution }}
{% endfor %}

---

{: .note-title }
> More content coming soon!
>
> I started by just including my degrees, but I want to add some more content here. I will use Jekyll document collections and Liquid templating to fill this with content. I can use the patterns I learned from the [Jekyll tutorial](https://jekyllrb.com/docs/collections/).

Please visit my [LinkedIn profile](https://www.linkedin.com/) or check out [what I'm working on](/what_im_working_on).