---
layout: page
title: publications
description: Brian M. Bot's publications
permalink: /publications/
---

***
***
<br>

This is a personally curated list of my peer-reviewed publications. 
Other sources include [PubMed query](http://www.ncbi.nlm.nih.gov/pubmed/?term=((((Bot+B%5BAuthor%5D)+OR+Bot+BM%5BAuthor%5D)+OR+Bot%2C+Brian%5BAuthor%5D)+OR+Bot%2C+Brian+M%5BAuthor%5D)+NOT+Le+Bot+B%5BAuthor%5D+NOT+Bot+BL%5BAuthor%5D){:target="_blank"}, [Google Scholar](https://scholar.google.com/citations?user=ZHXKPL0AAAAJ&hl=en){:target="_blank"}, and [ORCID](http://orcid.org/0000-0002-2412-6826){:target="_blank"}.

### Personal top 10 list (rev. chronological order)

{% for pub in site.data.pubTop10 %}
- {{ pub.authors }}. *{{ pub.title }}*. <u>{{ pub.journal }}</u>. {{ pub.year }}. [doi:{{ pub.doi }}](https://doi.org/{{ pub.doi }}){:target="_blank"}
{% endfor %}

***
***
<br>

### The rest of the best (rev. chronological order)

{% for pub in site.data.pubRest %}
- {{ pub.authors }}. *{{ pub.title }}*. <u>{{ pub.journal }}</u>. {{ pub.year }}. [doi:{{ pub.doi }}](https://doi.org/{{ pub.doi }}){:target="_blank"}
{% endfor %}

***
***
