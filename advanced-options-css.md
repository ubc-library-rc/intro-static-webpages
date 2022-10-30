---
layout: default
title: CSS
nav_order: 10
parent: Advanced Options
---

## 1. Custom CSS

We can also customize our CSS to get a still more personal touch. Earlier, we touched briefly on CSS - Cascading Style Sheets.

1
{: .label .label-step}
Create the following file in the following directories (remember our steps for creating a new file, including the folder it resides in):
```
assets/css/style.scss
```
{: .step}

2
{: .label .label-step}
Add the following to that file. This imports an existing theme to your CSS file.
```
---
---

@import "{{ site.theme }}";
```
{: .step}

3
{: .label .label-step}
Commit your changes. 
{: .step}

4
{: .label .label-step}
Refresh your published web page (the changes may take a minute to process).
{: .step}

5
{: .label .label-step}
Use your browser's 'inspect' option to see the html tags, classes, and IDs applied to your webpage. To find inspect, right click on the web page and click "Inspect."
{: .step}

## 2. Using tags and classes and IDs in CSS

Using a tag will apply the styling to all elements with that tag. Using a class will apply the styling to all elements with that class; more than one item can have the same class. Using an ID will change the styling of the object with that ID; IDs cannot be duplicated across objects. CSS rules apply styling from the most specific to the least specific, so styling asigned to an ID over rides that applied to a class, and styling applied to a class over rides that applied to a tag. 

Sometimes the theme itself will override the styling you're trying to apply. This can be overcome by applying `!important` after a specific attribute.
{: .note}

```
h1 {
  color: #e91e63; !important
}
```

1
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

What changes occurred in your web page?
