---
layout: default
title: Multiple Pages
nav_order: 11
parent: Advanced Options
---

# Multiple Pages

Some themes support navigation menus out of the box, making it easy to build a multi-page website.

1
{: .label .label-step}
Create a new file in your root directory called `about.md` and add the following YAML:

```
---
title: About
---
```
{: .step}

2
{: .label .label-step}
Update your `_config.yml` file to including the following; switching the theme to minima and indicating which files shoud appear in the navigation bar:

```
theme: minima

page_headers:
  - about.md

title: Title of your webpage.
```
{: .step}
