---
layout: page
title: People
permalink: /people/
subtitle: "Our research lab members"
feature-img: "assets/img/pexels/search-map.jpeg"
position: 2
tags:
---

{% for person in site.people %}
- [{{ person.name }}]({{ person.url }})  
  {{ person.role }}
{% endfor %}
