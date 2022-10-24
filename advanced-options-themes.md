---
layout: default
title: Themes
nav_order: 9
parent: Advanced Options
---

# Themes

A full list of themes compatible with GitHub Pages can be found here: [https://pages.github.com/themes/](https://pages.github.com/themes/).

Following each theme to its documentation page, you'll see instructions for adding that theme to your site.

## Adding a Theme

Step 1
{: .label .label-step}
create a file called `_config.yml` in your root directory.
{: .step}

Step 2
{: .label .label-step}
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

From the list of available themes, try adding one, like the Cayman, for example.
