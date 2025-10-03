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
{%raw%}{% assign about = site.pages | where_exp: "page", "page.path contains 'about/'" %}

{% include card-grid.html cards = about %}{%endraw%}
```

{% assign about = site.pages | where_exp: "page", "page.path contains 'about/'" %}
{% include card-grid.html cards = about %}
