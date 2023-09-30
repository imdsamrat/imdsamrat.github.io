---
layout: page
title: About Me
permalink: /about/
weight: 1
---

# **About Me**

Hi I am **{{ site.author.name }}**

<div align="justify">
I am a software engineer with over 6 years of work experience in software development domain mostly in a backend role. Skilled in Java, Spring boot, Python, Data structures and Algorithms. I pursued bechelor's degree in Computer Science and Engineering from <b><span style="color:rgb(0, 102, 153)">National Institute of Technology Allahabad, IN</span></b>.
<br>
I started learning programming at my college. There, I learnt about the endless possibilities of computer programs along with the enjoyment of challenging myself. In addition to being passionate about programming, I am eager to do things that I've never accomplished before and I strive to learn and improve on my skills every day.
</div>

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
