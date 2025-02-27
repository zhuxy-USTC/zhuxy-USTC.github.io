---
layout: archive
title: "Project Involved"
permalink: /project/
author_profile: true
---

<h2>Underway<h2>
<p style="font-family: 'Times New Roman', Times, serif;">
<ul>
<li> Dataflow Programming and Runtime System Framework Adapted to Domestic Heterogeneous System Architectures(Strategic Priority Research Program of Chinese Academy of Sciences) 
</li>
<ul>
<p>
**********************************************************

## Finished

<!-- {% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %} -->

<ul>
{% for post in site.projects reversed %}
  <div class="project-item">
    {% include archive-single-talk.html %}
  </div>
{% endfor %}
</ul>


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