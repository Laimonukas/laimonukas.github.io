---
layout: page
title: Landing Page
permalink: /
---

<div class="row">
    <div class="col-sm-3">
        {% include updated_landing.html %}
    </div>
    <div class="col-sm-9">
        <div class="row">
            {% include about/updated_skills.html title="Data Science" source=site.data.general-ds-skills %}
            {% include about/updated_skills.html title="Game Dev" source=site.data.general-gd-skills %}
        </div>

        <div class="row">
            {% include about/updated_timeline.html title="Experience:" source=site.data.minimal-experience-timeline %}
            {% include about/updated_timeline.html title="Education:" source=site.data.minimal-education-timeline %}
        </div>
    </div>
</div>

