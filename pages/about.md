---
layout: page
title: About
permalink: /about/
weight: 4
---

# **About Me** 

Hi I am **{{ site.author.name }}** :wave:,<br><br>
Abdul Hafiz Ramadan is a professional android developer with more than 4 years of experience in
software engineering. He has an educational background in Software Engineering and has been
passionate about coding since high school and has participated in many courses and activities
related to software engineering. During college he actively participated in software engineering
related activities such as being a Lecturer Assistant, Mini Android Bootcamp Mentor and actively
contributed to the Google Developer Student Clubs community as a head of core team for the
curriculum and developer division. He has solid skills in Java, Kotlin, and JavaScript and PHP
programming languages, he has a great interest in creating great user experiences and innovative
products.

{% include elements/button.html link="https://github.com/abdulhafizramadan-dev/abdulhafizramadan-dev.github.io/files/14156902/CV.Abdul.Hafiz.Ramadan.pdf" text="Download CV" %}

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Design & Prototyping Skills" source=site.data.other-skills %}
{% include about/skills.html title="Language Skills" source=site.data.languange-skills %}
</div>

## <span class="material-symbols-rounded">school</span> Education
<div class="timeline-body bg-themed">
    <div class="timeline-item">
        <div class="content">
          <h2>Telkom Insitute of Technology, Indonesia</h2>
          <h6 class="date">2020 - 2024</h6>
          <p>Bachelor of Computer Science at Software Engineering Department, Faculty of Informatics, as Best Graduate in Academics 2021 with a GPA of 3.90 out of 4.0.</p>
        </div>
      </div>
</div>

## <span class="material-symbols-rounded">work</span> Working Experience
<div class="row">
{% include about/timeline.html %}
</div>


## <span class="material-symbols-rounded">integration_instructions</span> Tech Contribution
<div class="timeline-body bg-themed">
    {% for item in site.data.experience %}
      <div class="timeline-item">
        <div class="content">
          <h2>{{ item.title }}</h2>
          <h6 class="date">{{ item.year}}</h6>
          <p>{{ item.description }}</p>
        </div>
      </div>
    {% endfor %}
</div>

<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Rounded:opsz,wght,FILL,GRAD@48,400,0,200" />