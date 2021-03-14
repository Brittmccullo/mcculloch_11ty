---
layout: template.html
title: Top 10 Studio Ghibli Movies
tags: page
---
# {{ title }}
<ol>
    {% for movie in movies -%}
    <li class="movie">{{ movie }}</li>
    {% endfor -%}
</ol>
