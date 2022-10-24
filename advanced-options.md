---
layout: default
title: Advanced Options
nav_order: 8
---

So far, our static site isn't looking like anything too special. There are a couple of ways that we can spruce up the look and feel of our site. The first is through the use of themes.

## Themes

A full list of themes compatible with GitHub Pages can be found here: [https://pages.github.com/themes/](https://pages.github.com/themes/).

Following each theme to its documentation page, you'll see instructions for adding that theme to your site.

### Adding a Theme

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

## Custom CSS

We can also customize our css to get a still more personal touch. Earlier, we touched briefly on css - creative style sheets.

Step 1
{: .label .label-step}
Create the following file in the following directories:
```
assets/css/style.scss
```
{: .step}

Step 2
{: .label .label-step}
add the following to that file:
```
---
---

@import "{{ site.theme }}";
```
{: .step}

Step 3
{: .label .label-step}
Use your browser's 'inspect' option to see the html tags, classes, and IDs applied to your webpage.
{: .step}

Using a tag will apply the styling to all elements with that tag. Using a class will apply the styling to all elements with that class; more than one item can have the same class. Using an ID will change the styling of the object with that ID; IDs cannot be duplicated across objects.  
CSS rules apply styling from the most specific to the least specific, so styling asigned to an ID over rides that applied to a class, and styling applied to a class over rides that applied to a tag.  
Sometimes the theme itself will override the styling you're trying to apply. This can be overcome by applying `!important` after a specific attribute:  
```
h1 {
  color: #e91e63; !important
}
```
{: .note}

