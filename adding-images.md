---
layout: default
title: Adding Images
nav_order: 2
parent: Markdown Introduction
---

## Adding images

Now that you've created a simple Markdown file, and GitHub Pages has turned it into an HTML web page, let's take a look at adding images (and other media). There are two main ways of adding media: using the URL of a web resource, or uploading it to the GitHub repository and creating a path to it.

First, let's create a folder in your GitHub repository to help keep your images organized.

## 1. Create a folder

There is no option to directly create a folder in GitHub; instead, a folder is created when you create a file and write a path to it. For instance, in order to create an **images** folder, you can create a file (e.g. temp.txt) and name it images/temp.txt.

1
{: .label .label-step}
In the top-level repository page, click Add file > Create new file
{: .step}

2
{: .label .label-step}
When prompted to name your file, enter images/temp.txt. Commit your changes. This will create a folder called images and an empty file inside of it called temp.txt (which can be deleted later, once you’ve moved more files into the images folder).
{: .step}

## 2. Upload a file

1
{: .label .label-step}
Make sure you are located within the images folder (you should see your temp.txt file).
{: .step}

2
{: .label .label-step}
Click Add file > Upload files.
{: .step}

3
{: .label .label-step}
Select an image from your computer to upload. If you want to download something from the web, try to use something that is not copyrighted or is royalty free ([e.g.Pexels](https://www.pexels.com/royalty-free-images/))
{: .step}

4
{: .label .label-step}
Commit your changes
{: .step}

## 3. Insert the image in your index.md file

1
{: .label .label-step}
Open up editing on your index.md file
{: .step}

2
{: .label .label-step}
Use the following Markdown syntax to insert your previously uploaded image to your document.

``![alt text](path to file "optional title")``

For instance:

``![A colourful garden](/images/gardens.png)``

{: .step}

3
{: .label .label-step}
Commit your changes.
{: .step}

4
{: .label .label-step}
Try out adding an image using the other option: by adding the URL to an image to your file. Use a Markdown guide if needed!
{: .step}
