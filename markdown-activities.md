---
layout: default
title: Markdown Activities
nav_order: 1
parent: Markdown Introduction
---

## Add a title and front matter
Let's add some front matter to your markdown file (we will discuss this in more detail in a later section). Front matter provides information about the web page's presentation and structure (title, layout, page order in a list, etc.). 
- Open your ```index.md``` file for editing. 
- Using the GitHub editor, copy the text below and paste it at the top (including the dashes):

```
---
title: <enter your title here>
layout: default
nav_order: 1
---
```

Don't worry if this information looks a bit weird when you preview the page--it won't appear on your final web page.  

## Use Markdown to add content to index.md
Using the [Mastering Markdown guide](https://guides.github.com/features/mastering-markdown/) and/or [markdownguide.org's Basic Syntax Guide](https://www.markdownguide.org/basic-syntax/) (or other guides you find on the web) as a reference, enter text beneath the front matter to create a fictional document that contains some of the following elements: 
- Headings of a number of different levels
- Bolded, italicized text 
- Insert an image from the web
- Insert the image that you uploaded to the ```images``` folder in this repository
- An ordered list
- A bulleted list
- A link to another website
- A snippet of code
- A table
- And finally, an emoji! (you can use the [Markdown Emoji cheat sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) as a reference)

### Some Notes
- Use the **Preview changes** tab to see (mostly) how it will look on your page. 
- Markdown doesn't add new lines to a document in the same way as a document editors like MS Word. Sometimes you might hit enter to start a new line in the editor, only to find that it has been added to the first paragraph when rendered. To avoid this you can try one of the following: 
  - Enter an extra blank line
  - Leave two blank spaces at the end of the sentence (this is interpretted as the end of a paragraph)
  - Insert the HTML tag ```<br>``` to create a line break in the rendered text. You can use multiple break tags to create more blank lines.  
<br>
**Commit your changes** and enjoy the products of your hard work!

## Create a second markdown page
The website you make in the next lesson will have two pages. Here, you are going to create the second page. 
- In the top level of your repository (remember, you can click the ```<> Code``` tab to get there), create a new markdown file. Name it as you wish, but ensure that it is free of spaces and special characters and ends in ```.md``` (e.g. ```pagetwo.md``` works just fine). 
- As done earlier, add front matter with a title. Set the ```nav_order``` value to 2 (this will inform GitHub Pages to make this the second menu item in your website), as shown below: 
```
---
title: <enter a different title here>
layout: default
nav_order: 2
---
```
- Add a few sentences and **commit your changes**.

### Some More Notes

You might find some things you would like to do that is possible only using HTML, such as symbols, subscripts and superscripts, and others. Here is one resource on how to format HTML to insert symbols: [HTML Symbols reference page](https://www.w3schools.com/html/html_symbols.asp)
Additional resources are widely available on the web.
