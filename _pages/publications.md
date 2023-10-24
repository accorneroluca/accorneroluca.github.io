---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

I am a differential geometer who studies geometric structures by investigating their symmetries. The naive idea is that a lot of information about a geometric structure can be extracted from its set of symmetries, assuming this set is well behaved. This idea appears ubiquitously in geometry. In the past, I focused on the following two topics:

* the relationship between symmetries and conserved quantities in mathematical physics -- the starting point being the **Noether theorem**;
* constructing cohomological invariants for geometric structures on manifolds with a well behaved set of symmetries -- having in mind Haefliger's construction of **characteristic classes for foliated manifolds**.

One of my main interests are **higher structures** in differential geometry. In particular, **Lie groupoids** and **multiplicative structures** over them, as well as the theory of **Morita equivalences** and **differentiable stacks**, are central in my research.

I am also very much interested in **Poisson geometry** (especially its intereaction with almost complex geometry) and **Jacobi geometry**. Furthermore, I am working on a version of **Morse theory** that captures the homotopy type of a **hyperplane field** on a manifold.

## Publications

Below is the list of my publications and manuscripts in preparations.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% if author.orcid %}
  See also my <u><a href="{{ author.orcid }}">ORCID profile</a>.</u>
{% endif %}


### In preparation
<ul>{% for post in site.publications reversed %}
  {% if post.status == 'in preparation' %}
    <li> {% include archive-single-publication.html %}</li>
  {% endif %}
{% endfor %} </ul>

### Preprints
<ul>{% for post in site.publications reversed %}
  {% if post.status == 'preprint' %}
    <li>{% include archive-single-publication.html %}</li>
  {% endif %}
{% endfor %} </ul>

### Peer reviewed
<ul>{% for post in site.publications reversed %}
  {% if post.status == 'peer-reviewed' %}
    <li>{% include archive-single-publication.html %}</li>
  {% endif %}
{% endfor %}</ul>