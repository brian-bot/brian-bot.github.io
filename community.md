---
layout: page
title: community
description: Brian M. Bot's community activities
permalink: /community/
---

***
***
<br>

<img src="/images/sudan.jpg" alt="Brian in Sudan" style="width:80%;display:block;margin-left:auto;margin-right:auto">

<br>

***
***
<br>

I am committed to being an active participant in the open science community. Here is a list of community activities I have been involved with:

{% for comm in site.data.community %}
- **{{ comm.role }}**. *{{ comm.activity }}*. {{ comm.date }}
{% endfor %}

***
***
