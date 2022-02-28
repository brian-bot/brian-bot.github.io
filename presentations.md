---
layout: page
title: presentations
description: Brian M. Bot's presentations
permalink: /presentations/
---

***
***
<br>

<figure>
<img src="/images/summittalk.jpg" alt="Brian at CC Summit" style="width:80%;display:block;margin-left:auto;margin-right:auto">
<figcaption style="text-align: center"> 2017 Creative Commons Summit: Toronto, CAN </figcaption>
</figure>

***
***
<br>

I have been invited to a number of national and international events to speak on a variety of topics such as open science, biomedical research, data sharing, data governance, clinical trials, and the effect of emerging technologies (and decentralization) on the scientific ecosystem. 

### Personal top 10 list (rev. chronological order)

{% for pres in site.data.presTop10 %}
  {% if pres.role == null %}
- *{{ pres.talkTitle }}*. <u>{{ pres.talkVenue }}</u>. {{ pres.talkLocation }}. {{ pres.talkDate }}
  {% else %}
- **{{ pres.role }}**. *{{ pres.talkTitle }}*. <u>{{ pres.talkVenue }}</u>. {{ pres.talkLocation }}. {{ pres.talkDate }}
  {% endif %}
{% endfor %}

***
***
<br>

### The rest of the best (rev. chronological order)

{% for pres in site.data.presRest %}
  {% if pres.role == null %}
- *{{ pres.talkTitle }}*. <u>{{ pres.talkVenue }}</u>. {{ pres.talkLocation }}. {{ pres.talkDate }}
  {% else %}
- **{{ pres.role }}**. *{{ pres.talkTitle }}*. <u>{{ pres.talkVenue }}</u>. {{ pres.talkLocation }}. {{ pres.talkDate }}
  {% endif %}
{% endfor %}

***
***
