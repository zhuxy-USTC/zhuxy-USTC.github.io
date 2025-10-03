---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
hide_title: true
---

<h2 >📨 Submitted Paper</h2>
<div style="font-family: 'Times New Roman', Times, serif;">
<ul>
<li>As <strong>first-author</strong>, the paper "swPredicter: A Data-Driven Performance Model for Distributed Data Parallelism Training on Large-Scale HPC Clusters" has been submitted to Performance Evaluation: An International Journal <strong>(Elsevier PE)</strong></li>
<li>As <strong>first-author</strong>, the paper "Accelerating Large-Scale Distributed Training via Chunk-Wise Gradient Sparsification and Pipelined Communication" has been submitted to Journal of Computer Science and Technology  <strong>(JCST)</strong></li>
</ul>
</div>

********************************************************

<h2>📝 Published Paper</h2>
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


