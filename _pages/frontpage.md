---
permalink: /
layout: home
title: 
list_title: 
---

<style>
    .container{
        display:flex;
        align-items: center;
        justify-content: left;
        padding-top: 20px;
        padding-bottom: 20px;
    }
    .img{
        float:left;
    }
    .text{
        width:512px;
        font-size: 15px;
        padding-left: 20px;
    }
</style>
---
<div class="container">
    <img src="../assets/imgs/pp.jpg" width=256px height=256px>
<div class="text">
Welcome to my page, this is where I showcase my art, research and some thoughts and processes about everything. I am a computer graphics researcher, currently a PhD studet at Texas A&M University working with <a href="http://people.tamu.edu/~ergun/">Dr. Ergun Akleman</a> on weaving structures, ray tracing and volumetric decompositions. I graduated from <a href="https://w3.bilkent.edu.tr/bilkent/">Bilkent University</a> with a degree in Electrical and Electronics Engineering. 
</div>
</div>
---
# <a href="../assets/pdfs/TolgaYildiz_CV.pdf" target="_blank">CV</a>
---
# Education
{% include_relative education.md %}
---
# Experience
{% include_relative experience.md %}
---
# [Teaching](teaching_header.md)
{% include_relative teaching.md %}
---



