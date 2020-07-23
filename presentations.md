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

I have been an invited speaker at a number of national and international events to share my experiences living at the intersection of biomedical research, technology, and policy. See below for a reverse chronological ordered list of events where I have been invited to speak:

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
