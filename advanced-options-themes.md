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

1
{: .label .label-step}
Create a file called `_config.yml` in your root directory.
{: .step}

2
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

3
{: .label .label-step}
For the next activities, we will be using the Minima theme. Please add or change your theme accordingly (by replacing anything you have in your file with the following):

```
theme: minima
```

{: .step}
