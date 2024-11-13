---
layout: organization
permalink: /organization/
title: Organization
description:
nav: true
nav_order: 5
---

# Chairs

<div class="card-deck card-deck-org">
{% for chair in site.data.chairs.chairs %}
    <div class="card card-org">
        <img class="card-img-top" src="/assets/img/chairs/{{ chair.image }}" alt="{{ chair.name }}">
        <div class="card-body">
            <h4 class="card-title">{{ chair.name }}</h4>
            <h5>{{ chair.affilitation }}</h5>
            <h6>{{ chair.role }}</h6>
        </div>
    </div>
{% endfor %}

</div>

<!-- split -->

# Sponsors
