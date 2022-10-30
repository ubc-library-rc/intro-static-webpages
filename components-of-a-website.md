---
layout: default
title: Website Structure
nav_order: 6
---

# Components of a Web Site

Now that we've seen how simple it is to create a basic (albeit empty) static website with GitHub pages, it's worth talking a bit more about how web pages and web sites are structured. We'll then show you how to add folders and files to your GitHub repository, and how to edit the files to produce structured web pages with content.

A web page can be broken down a couple of different ways. We're going to first look at the url structure to understand where content sits and how content is related in a website. Then we'll talk about the pieces that provide the look and feel of a web page.

## Website

A website refers to all the web pages that make up a domain. A given web page is accessible through a URL - Uniform Resource Locator. A URL is made up of a series of components:



* A scheme: https: - this defines the exchange protocol, or rather, sets the language that your web browser and the server that is sending your web browser the web page will use - without establishing a protocol or standard language for communicating, things would go haywire. Other schemes you might have hear of include http or ftp
* A domain example.com - this is the name of the website and has a matching numeric address behind it.  Each address and domain name are unique. 
* A path - this is like the folder structure on your computer and tells us in what folder, on the server, the content is that you're looking at.
* A resource - the file that you're viewing, that is, the web page or image you're looking at.

## Web page

A web page is the resource that you're viewing. Web pages are built using structure and aesthetics like most any document we're used to working with.

### Structure

The structure of a web page is written in HTML and it defines elements in a page. Common structures include headers, lists, and tables. Structures also group content together. Most web pages are divided into at least 3 groups of content, just like an academic paper; there's a banner, or header, the body, or content, and the footer.

#### HTML

<table>
  <tr>
   <td>Banner<br />Often an image with a navigation menu.
   </td>
    <td style="background-color:#8fcfcb;text-align:center;"><button style="background-color:#ffffff;border:none;">About</button> <button style="background-color:#ffffff;border:none;">Contact</button> <button style="background-color:#ffffff;border:none;">My Research</button>
   </td>
  </tr>
  <tr>
   <td>Content<br />What you want to tell people. It comprises headers, lists, tables etc. and potentially more sections of grouped content.
   </td>
   <td>
     <h2 style="text-align:center;">My Page!</h2>
     <p>My List</p>
    <ul>
      <li>One thing</li>
      <li>Two things</li>
      <li>Three things</li>
    </ul>
    <p>My Table</p>
    <table>
      <tr>
        <td>Person</td>
       <td>Age (yrs)</td>
       <td>Height (cm)</td>
      </tr>
      <tr>
        <td>A Sitalot</td>
        <td>23</td>
        <td>185</td>
      </tr>
      <tr>
        <td>B Standalot</td>
        <td>18</td>
        <td>160</td>
      </tr>
    </table>
    </td>
  </tr>
  <tr>
   <td>Footer<br />often a band of colour with contact information.</td>
   <td style="background-color:#8fcfcb;text-align:center;color:#ffffff;">mail@mail.ubc.ca<br />Rm 217<br />UBC Library</td>
  </tr>
</table>


Written in html, this would look something like

<table>
  <tr>
   <td>
     &lt;div id = "header"><br />
     &nbsp;&nbsp;&nbsp;&lt;div id = "nav" role = "navigation"><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;ul><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;li>About</li><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;li>Contact</li><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;li>My Research</li><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;/ul><br />
     &nbsp;&nbsp;&nbsp;&lt;/div><br />
     &lt;/div><br />
   </td>
   <td style="background-color:#8fcfcb;text-align:center;"><button style="background-color:#ffffff;border:none;">About</button> <button style="background-color:#ffffff;border:none;">Contact</button> <button style="background-color:#ffffff;border:none;">My Research</button>
   </td>
  </tr>
  <tr>
   <td>
     &lt;div id = "body"><br />
     &nbsp;&nbsp;&nbsp;&lt;h1 id = "title">My Page!&lt;/h1><br />
     &nbsp;&nbsp;&nbsp;&lt;p>My List&lt;/p><br />
     &nbsp;&nbsp;&nbsp;&lt;ul><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;li>One thing&lt;/li><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;li>Two things&lt;/li><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;li>Three things&lt;/li><br />
     &nbsp;&nbsp;&nbsp;&lt;/ul><br />
     &nbsp;&nbsp;&nbsp;&lt;p>My Table&lt;/p><br />
     &nbsp;&nbsp;&nbsp;&lt;table><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;thead><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;tr><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;th>Person&lt;/th><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;th>Age (yrs)&lt;/th><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;th>Height (cm)&lt;/th><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;/tr><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;/thead><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;tbody><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;tr><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;td>A Sitalot&lt;/td><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;td>23&lt;/td><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;td>185&lt;/td><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;/tr><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;tr><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;td>A Sitalot&lt;/td><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;td>18&lt;/td><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;td>160&lt;/td><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;/tr><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;/tbody><br />
     &nbsp;&nbsp;&nbsp;&lt;/table><br />
     &lt;/div><br />
   </td>
   <td>
     <h2 style="text-align:center;">My Page!</h2>
     <p>My List</p>
    <ul>
      <li>One thing</li>
      <li>Two things</li>
      <li>Three things</li>
    </ul>
    <p>My Table</p>
    <table>
      <tr>
        <td>Person</td>
       <td>Age (yrs)</td>
       <td>Height (cm)</td>
      </tr>
      <tr>
        <td>A Sitalot</td>
        <td>23</td>
        <td>185</td>
      </tr>
      <tr>
        <td>B Standalot</td>
        <td>18</td>
        <td>160</td>
      </tr>
    </table>
   </td>
  </tr>
  <tr>
   <td>
     &lt;div id = "footer"><br />
     &nbsp;&nbsp;&nbsp;&lt;p><br />&lt;a>href="mailto:mail@mail.ubc.ca">mail@mail.ubc.ca&lt;/a><br />&lt;/p><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;p>Rm 217&lt;/p><br />
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;p>UBC Library&lt;/p><br />
     &nbsp;&nbsp;&lt;/div><br />
    </td>
    <td style="background-color:#8fcfcb;text-align:center;color:#ffffff;">mail@mail.ubc.ca<br />Rm 217<br />UBC Library</td>
  </tr>
</table>


### Style

#### CSS

CSS - which stands for cascading style sheets - provide aesthetics; colours, position, fonts etc. 

The above html would be accompanied by a stylesheet that dictates this formatting by indicating how various components should be styled.

#header {  
&nbsp;&nbsp;&nbsp;&nbsp;background-image: "tiger.jpg";  
}

h1 {  
&nbsp;&nbsp;&nbsp;&nbsp;color: "blue";  
&nbsp;&nbsp;&nbsp;&nbsp;font-size: 24pt;  
}

## Advantages of GitHub Pages

GitHub Pages allows flexibility in how we code web pages. It allows us to write in html if we want, but if the above demo is any indication, html is extremely verbose, and there can be a fair bit to learn.

Alternatively, we can write in Markdown, a very simple, structured, plain text format. Behind the scenes, GitHub pages, with the aid of a service called Jekyll, translates Markdown to html.

Markdown allows us to use a subset of the structural elements that html has available. Being a subset helps to keep it simple. Knowing a little bit about html, however, can help to take the structure of your web pages to the next level. And knowing a little bit about css will help you to create a custom look and feel. 

In this workshop, we will use Markdown to write some files that will be turned by GitHub Pages into HTML, and into a web page. 
