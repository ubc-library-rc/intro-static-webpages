---
layout: default
title: Advanced Options
nav_order: 8
has_children: true
---

So far, our static site isn't looking like anything too special. There are a couple of ways that we can spruce up the look and feel of our site.  This means playing around with YAML. YAML is basically a series of key value pairs and is wrapped by three dashes `---` placed at the top of your document:

```
---
title: About
---
```

YAML is space sensitive, so no spaces before the key, one space after the colon, and if you need to indent, an indent consists of two spaces.
{: .note}

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

Using a tag will apply the styling to all elements with that tag. Using a class will apply the styling to all elements with that class; more than one item can have the same class. Using an ID will change the styling of the object with that ID; IDs cannot be duplicated across objects. CSS rules apply styling from the most specific to the least specific, so styling asigned to an ID over rides that applied to a class, and styling applied to a class over rides that applied to a tag. Sometimes the theme itself will override the styling you're trying to apply. This can be overcome by applying `!important` after a specific attribute.
{: .note}

```
h1 {
  color: #e91e63; !important
}
```

Step 4
{: .label .label-step}
Update your `style.scss` document accordingly:
```
---
---

@import "{{ site.theme }}";

h1 {
  color: #e91e63;
}
```
{: .step}

## Multiple Pages

Some themes support navigation menus out of the box, making it easy to build a multi-page website.

Step 1
Create a new file in your root directory called `about.md` and add the following YAML:

```
---
title: About
---
```
{: .step}

Step 2
Update your `_config.yml` file to including the following; switching the theme to minima and indicating which files shoud appear in the navigation bar:

```
theme: minima

page_headers:
  - about.md

title: Title of your webpage.
```
{: .step}
