---
title: Research & Professional Experience
layout: page
permalink: /research.html
---

# Research and Professional Experience

<div class="row my-3 py-3 {{ include.container-styles }}">
    {%- assign items = site.data[site.metadata] | where_exp: 'item', 'item.subject contains "research"' | sort: "date_range" -%}

        {% for item in items %}
            <div class="col-md-4">
            {% include feature/image.html objectid=item.objectid %}
            </div>
        {% endfor %}
    </div>