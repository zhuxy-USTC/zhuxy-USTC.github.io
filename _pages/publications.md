---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Submitted Paper
* As **first-author**, the paper "swPredicter: A Data-Driven Performance Model for Distributed Data Parallelism Training on Large-Scale HPC Clusters" has been submitted to IEEE Transactions on Parallel and Distributed Systems **(TPDS)**
* As **second-author**, the paper "SwFormer: Enabling Faster Foundation Models on new Sunway Supercomputer via Holistic Kernel Tiling and Scheduling" has been submitted to Journal of Computer Science and Technology **(JCST)**

********************************************************
## Published Paper
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
  {% endfor %}</ul>



<!-- {% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %} -->

{% include base_path %}

<!-- New style rendering if publication categories are defined -->
{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}


