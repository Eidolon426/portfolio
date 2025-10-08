---
title: "Local News"
layout: base
date: 2025-10-03
header-title: Introduction
header-position: 0px
---

{% assign articles = site.pages | where_exp: "page", "page.path contains 'articles/'" %}
{% include card-grid.html cards = articles%}

{% assign articles = site.pages | where_exp: "page", "page.path contains 'articles/'" 
%}
{% include card-grid.html 
cards = articles
%}

