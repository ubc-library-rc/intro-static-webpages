---
layout: default
title: Advanced Options
nav_order: 8
---

So far, our static site isn't looking like anything too special. There are a couple of ways that we can spruce up the look and feel of our site. The first is through the use of themes.

## Themes

A full list of themes compatible with GitHub Pages can be found here: [https://pages.github.com/themes/](https://pages.github.com/themes/).

To add a theme:

Step 1 {: .label .label-step}
create a file called `_config.yml` in your root directory.
{: .step}

Step 2 {: .label .label-step}
Add the following to that file, replacing `theme-name` with the theme you'd like to use:

```
theme: theme-name
```

Some themes are added with the following, again, replacing `theme-name` with the theme you'd like to use:

```
remote_theme: theme-name
plugins:
- jekyll-remote-theme
```
{: .step}
