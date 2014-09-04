---
layout: page
title: Program
permalink: /program/
---

####Program####

You can register for SenSys 2014 <a href="https://www.regonline.com/Register/Checkin.aspx?EventID=1595424">here</a>.

####Accepted Papers####

<ul class="paper">
{% for paper in site.data.papers %}
  <li>
    <span class="papertitle">{{ paper.title }}</span> <br/> <span class="authors">{{ paper.authors}}</span><br/>
    {{ paper.affiliation }}
    </li>
{% endfor %}

</ul>
