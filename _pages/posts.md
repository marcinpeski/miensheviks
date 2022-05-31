---
layout: archive
title: "Posts"
permalink: /posts/
author_profile: true
---


{% include base_path %}

<ol>
  {% for post in site.posts %}
    
      <li>{% include archive-single.html %}</li>
    
  {% endfor %}
</ol>
