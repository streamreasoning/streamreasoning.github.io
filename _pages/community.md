---
layout: page
title: community
permalink: /community/
description: Our growing community
nav: true
display_categories: [work, fun]
horizontal: false
---
  
<div class="projects">
  <div class="grid">
    {%- for coauthor in site.data.coauthors -%}
    {% assign name=coauthor[0] %}
    <h1>{{name}}</h1>
      {%- for person in site.data.coauthors[name] -%}
        {% include person.html %}
      {%- endfor %}
    {%- endfor %}
  </div>
</div>