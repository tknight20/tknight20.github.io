---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
I am a Santa Barbara native who loves to learn and to create. I am currently studying engineering and computer science at Westmont College. When I am not doing coursework, you can usually find me surfing, playing guitar, or at the beach.

## **My Career**
Interested in what my career and education have been like beyond what is shown below? Take a look at my CV!

{% include elements/button.html link="https://drive.google.com/file/d/1poedjSEr2Ex7WRLvbnpchJFzbD7ETNe6/view?usp=sharing" text="CV" block=true %}

<div class="row">
{% include about/skills.html title="Engineering Skills" source=site.data.engineering-skills %}
</div>
<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
