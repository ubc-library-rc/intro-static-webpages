---
layout: default
title: CSS
nav_order: 10
parent: Advanced Options
---

# Custom CSS

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
