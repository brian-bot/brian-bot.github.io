---
layout: page
title: community
description: Brian M. Bot's community activities
permalink: /community/
---

***
***
<br>

<figure>
<img src="/images/sudan.jpg" alt="Brian in Sudan" style="width:90%;display:block;margin-left:auto;margin-right:auto">
<figcaption style="text-align: center"> 2018 East Africa Open Science Tour: Khartoum, Sudan </figcaption>
</figure>

***
***
<br>

I am an active participant in a variety of research communities. 

### Personal top 10 list (rev. chronological order)

{% for comm in site.data.communityTop10 %}
- **{{ comm.role }}**. *{{ comm.activity }}*. {{ comm.date }}
{% endfor %}

***
***
<br>

### The rest of the best (rev. chronological order)

{% for comm in site.data.communityRest %}
- **{{ comm.role }}**. *{{ comm.activity }}*. {{ comm.date }}
{% endfor %}

***
***
