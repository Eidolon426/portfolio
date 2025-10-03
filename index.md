---
title: Getting Started
layout: base
date: 2024-12-02
---

```
# Simon Ruybalid
```
```
## Biography
```
```
## Contact
```

```
{%raw%}{% assign essays = site.pages | where_exp: "page", "page.path contains 'essays/'" %}

{% include card-grid.html cards = essays %}{%endraw%}
```

{% assign essays = site.pages | where_exp: "page", "page.path contains 'essays/'" %}
{% include card-grid.html cards = essays %}
