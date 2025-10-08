---
title: "Local News"
layout: base
date: 2025-10-03
header-title: Introduction
header-position: 0px
header-image: /assets/images/spring.jpg
---

### Local News



<br/>
{% assign articles = site.pages | where_exp: "page", "page.path contains 'articles/'" %}
{% include card-grid.html cards = articles%}
<br/>


{% assign cards = page.cards %}

{% include card-list.html 
cards = cards 
%}


