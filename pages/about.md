---
layout: page
title: About
permalink: /about/
weight: 3
---


{% include social.html %}


# **About Me**

Hello everyone, my name is **{{ site.author.name }}**,<br>
I'm currently pursuing a specialization in **Data Science** and **Machine Learning** to echance my analytical, technical expertice. I am a **Data Science Enthusiast** with a passion for **Game Development** and hopefully I will be able to combine both of them in the future. I am also a **Computer Science** graduate with a tons of experience in platform monitoring, incident management, complemented by leadership and team management skills. I am a **quick learner** and **problem solver** with a **can-do attitude**. I am always looking for new challenges and opportunities to learn and grow.

## **Professional Aspirations**

I am looking for opportunities in the fields of **Data Science**, **Machine Learning**, **Game Development**,- for a role where I can apply my skills and knowledge to solve real-world problems, challenge myself and grow as a professional.  

<div class="row">
    {% include about/updated_skills.html title="Programming Skills" source=site.data.programming-skills %}
    {% include about/updated_skills.html title="Libraries" source=site.data.libraries-skills %}
    {% include about/updated_skills.html title="Data Visualization Libraries" source=site.data.data-viz-skills %}
    {% include about/updated_skills.html title="Tools" source=site.data.tools-skills %}
    {% include about/updated_skills.html title="Other" source=site.data.other-skills %}
</div>

<div class="row">
    {% include about/updated_timeline.html title="Experience:" source=site.data.experience-timeline %}
    {% include about/updated_timeline.html title="Education:" source=site.data.education-timeline %}
</div>