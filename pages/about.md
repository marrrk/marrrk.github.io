---
layout: page
title: about
permalink: /about/
weight: 1
---

# **About Me**

Hi, I'm **{{ site.author.name }}** :wave:,<br>
I was born in Nairobi, Kenya on the 14th of April 1998. After 3 years, we moved to Gaborone, Botswana which is where I have spent majority of my life. After completing Secondary school, I found myself at the University of Cape Town studying Mechatronics Engineering which I completed in 2020. In that time, I homed in on my interest in Electronics, Hardware and Embedded Systems. I then decided to pursue a Master's degree with the goal of learning more and ultimately bettering my skillset in these fields.


I have a passion for helping people and aim to combine that with my skills as an engineer to produce solutions that make life a better place for the human populous.


<div class="row">
    {% include 
        about/skills.html title="Programming Skills" source=site.data.programming-skills 
    %}

    {% include 
        about/skills.html title="Engineering Design Skills" source=site.data.engineering-skills 
    %}
</div>


# Tools, Platforms and Protocols
The following is a list of the various platforms I have worked with over the course of my relatively short career:
<div class="row">
    {% include 
        about/tools.html
    %}
</div>