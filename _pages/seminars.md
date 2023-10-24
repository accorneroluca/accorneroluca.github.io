---
layout: archive
title: "Conferences and seminars"
permalink: /seminars/
author_profile: true
---

Below is a list of conferences and seminars of which I have been (co-)organizer.

{% include base_path %}

Conferences
-

{% for post in site.seminars reversed %}
  {% if post.type == 'Conference' %}
    {% include archive-single-seminar.html %}
  {% endif %}
{% endfor %}

Seminars
-

{% for post in site.seminars reversed %}
  {% if post.type == 'Seminar' %}
    {% include archive-single-seminar.html %}
  {% endif %}
{% endfor %}