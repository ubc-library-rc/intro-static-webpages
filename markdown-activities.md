---
layout: default
title: Markdown Activities
nav_order: 2
parent: Markdown Introduction
---

## Add a title and front matter

You will now start editing your markdown file. First, you will be adding something called **front matter** (more specifically, a YAML front matter block). The front matter must be at the top of the page and must take the form of valid YAML set between triple-dashed lines. It maintains metadata for the page and is used by the underlying static site tool (Jekyll) when building your website from the files. Any front matter won't appear on the published webpage. More on YAML later.

1
{: .label .label-step}
Open your ```index.md``` file for editing.
{: .step}

2
{: .label .label-step}
Using the GitHub editor, copy (or type) the text below and paste it at the top (including the dashes):
{: .step}

```
---
title: <enter your title here>
layout: default
nav_order: 1
---
```

## Use Markdown to add content to index.md

Now let's add some content to the body of the file--this is what will appear on your published webpage. 

1
{: .label .label-step}
Open up a Markdown guide. You can use the [Mastering Markdown guide](https://guides.github.com/features/mastering-markdown/) and/or [markdownguide.org's Basic Syntax Guide](https://www.markdownguide.org/basic-syntax/) (or other guides you find on the web).
{: .step}

2
{: .label .label-step}
Add some text in **bold** and some text that is _italicized_.
{: .step}

3
{: .label .label-step}
Add a heading (any level), followed by a bulleted list.
{: .step}

4
{: .label .label-step}
Insert the image that you uploaded earlier OR insert an image from the web.
{: .step}

### Some Notes
- Use the **Preview changes** tab to see (mostly) how it will look on your page. 
- Markdown doesn't add new lines to a document in the same way as a document editors like MS Word. Sometimes you might hit enter to start a new line in the editor, only to find that it has been added to the first paragraph when rendered. To avoid this you can try one of the following: 
  - Enter an extra blank line
  - Leave two blank spaces at the end of the sentence (this is interpretted as the end of a paragraph)
  - Insert the HTML tag ```<br>``` to create a line break in the rendered text. You can use multiple break tags to create more blank lines.  
<br>
**Commit your changes** and enjoy the products of your hard work!

## Create a second markdown page
Prompt: How would you create a second markdown page for your website?

What steps would you need to take? What would you need to change in the front matter?

### Some More Notes

You might find some things you would like to do that is possible only using HTML, such as symbols, subscripts and superscripts, and others. Here is one resource on how to format HTML to insert symbols: [HTML Symbols reference page](https://www.w3schools.com/html/html_symbols.asp)
Additional resources are widely available on the web.
