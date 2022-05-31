---
layout: archive
title: "Council meetings"
permalink: /councilmeetings/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<ol>
  {% for post in site.councilmeetings reversed %}
    
      <li>{% include archive-single-publications.html %}</li>
    
  {% endfor %}
</ol>
