---
layout: default
title: Multiple Pages
nav_order: 11
parent: Advanced Options
---

## Multiple Pages

How do you make a second page and how do you display it in a navigation menu?

As mentioned before, making a second page requires you to create a second Markdown file (remember the extension in .md!). You will have a YAML front matter block on this page as well, where you can set values such as title and navigation order. 

Next, if you are using a theme that has a navigation menu out-of-the-box, it is easy to have that second page displayed in its navigation menu.

1
{: .label .label-step}
Create a new file in your root directory called `about.md` and add the following YAML:

```
---
title: About
layout: default
nav_order: 1
---
```
{: .step}

2
{: .label .label-step}
Open your `_config.yml` file created earlier, where you added a **theme**. Edit the file with the following. (You will be switching to the minima theme for this activity.)

```
theme: minima

page_headers:
  - about.md

title: Title of your webpage.
```
{: .step}

3
{: .label .label-step}
Wait a minute and referesh your published webpage. You should now see your new About page appear in the navigation menu, as well as the new minima theme. 
{: .step}
