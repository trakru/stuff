---
layout: default
title: Blog
---

![image](/assets/img/office.jpg)
Founded in 2005, Broadband Holdings, LLC provides consulting and engineering services to the broadband industry. BBH partners with several mid-tier cable operators, such as Shrewsbury Electric & Cable Operations, Stowe Cable Systems and Trans-Video, with a multitude of services from planning, to developing bid specifications, to managing projects, to integrating turn-key 'end to end' highly scalable broadband networks utilizing "Best in Class" components. The diverse team at BBH has the skill sets necessary to help our customers succeed.

<h2>Latest Posts</h2>

<ul>
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>