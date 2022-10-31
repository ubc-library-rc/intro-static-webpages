---
layout: default
title: Write Files in Markdown
nav_order: 1
parent: Markdown Introduction
---

## 1. Create a Markdown file (index.md)

Remember how GitHub Pages is currently using your README.md file to generate the homepage of your website? Now we will create an **index.md** file. If an **index.md** file exists in your repository, GitHub Pages will automatically use it (instead of the README.md file) as the homepage.

1
{: .label .label-step}
In the top-level repository page (which you can navigate to by clicking the &lt;> Code tab), click Add file > Create new file
{: .step}

2
{: .label .label-step}
When prompted to name your file, title it index.md. This creates an empty text file that GitHub will assume contains Markdown code. Make sure you have the .md extension or else the page won't be built correctly!
{: .step}

3
{: .label .label-step}
Scroll down to the Commit new file section. 
{: .step}

## 2. Add a title and front matter

Now let's get to editing your markdown file! First, you will be adding something called **front matter** (more specifically, a YAML front matter block). The front matter must be at the top of the page and must be set between triple-dashed lines. This front matter maintains metadata for the page and is used by the underlying static site tool (Jekyll) when building your website from the files. Front matter won't appear on the published webpage. 

Let's add three things: title, layout, and nav_order.

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

## 3. Use Markdown to add content to index.md

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
Use one more styling syntax of your choosing.
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

What steps would you need to take? 

### Some More Notes

You might find some things you would like to do that is possible only using HTML, such as symbols, subscripts and superscripts, and others. Here is one resource on how to format HTML to insert symbols: [HTML Symbols reference page](https://www.w3schools.com/html/html_symbols.asp)
Additional resources are widely available on the web.
** This is not the only way you can style your web page: using themes, CSS, Javascript, etc. are additional, though more advanced, methods.
