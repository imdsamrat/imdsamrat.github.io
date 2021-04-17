---
layout: page
title: About Me
permalink: /about/
weight: 1
---

# **About Me**

Hi I am **{{ site.author.name }}**
<div align="justify">
I am a software engineer with over 3.5 years of work experience in software development domain mostly in a backend role. Skilled in Java, C/C++, Python, data structures and algorithms. I pursued my bechelor's degree in Computer Science and Engineering from <b><span style="color:rgb(0, 128, 255)">National Institute of Technology Allahabad, IN</span></b>.
<br>
I started learning programming at my college. Slowly, I learnt about the endless possibilities of computer programs along with the enjoyment of challenging myself to make my programs work. In addition to being passionate about programming, I am eager to challenge myself to do things I've never accomplished before and I strive to learn and improve on my skills every day.
</div>

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>