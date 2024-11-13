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
    <div class="card card-org item-expand">
        <img class="card-img-top shadow" src="/assets/img/chairs/{{ chair.image }}" alt="{{ chair.name }}">
        <div class="card-body">
            <h4 class="card-title">{{ chair.name }}</h4>
            <h5>{{ chair.affilitation }}</h5>
            <h6>{{ chair.role }}</h6>
        </div>
    </div>
{% endfor %}
</div>

{% if site.data.chairs.program_committee%}

<hr>

# Program Committee

{% for member in site.data.chairs.program_committee %}

- {{ member.name }}, {{ member.affiliation }}

{% endfor %}

<hr>
{% endif %}

<!-- split -->

# Sponsors

Sponsors will be announced soon!
