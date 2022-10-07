---
layout: default
title: GitHub Activities
nav_order: 6
parent: GitHub Introduction
---

Step 1: Create a new GitHub repository
{: .label .label-step}
First, set up a new project on GitHub. This will eventually be turned into a website. The repository is where all the folders and files, including any images or media, for your project will go. The repository is also a way for others to view the “raw” content of your website and for collaborators to contribute to a shared repository. By default, GitHub will track changes to materials that are stored in a repository. While you can build your website from a subsection of your repository, it is a good practice to create a new repository for each project or website.
{: .step}
* Ensure you have created a GitHub account and are logged in.
* From your GitHub main page, click on the green New Repository button. 
    * Provide a name for your repository. This name will be part of the URL of your repository as well as part of the address of your published website, unless you choose a custom domain.
        * The repository URL will take the form: [https://github.com/](https://github.com/)&lt;your-github-username>/&lt;your-repo-name>
* Check the box to Initialize this repository with a README
    * NOTE: Your README file is a plain text file (same as a .txt file) that typically contains descriptive information about your repository (Who made it? What does it contain? What is it for?, etc.).
    * You can also add a README file later if you like.
* Click the Create repository button
* Your browser will now open to the top-level page of the repository. Your repository will contain one file: README.md.
{: .step}

Step 2
{: .label .label-step}
Do this other thing
{: .step}



#### 2. Set up GitHub Pages 

In this step, you will enable the GitHub Pages feature in your repository settings. GitHub Pages knits together your repository files and turns them into an HTML site.

* Open the Settings Tab in your repository. 
* Go to Settings > Options. Scroll down to the GitHub Pages section.
    * For the Source, set Branch:main and set the folder to /(root) and click Save. This directs GitHub pages to the top-level of your repository for your website content.
* You should see a link to your website appear in the GitHub Pages section. That link is now live.
    * NOTE: You may initially receive a 404 error as the website is being built.

Your website will look pretty empty at this stage. Keep this tab open so when you make changes in this workshop, you can refresh the page and view your changes.

#### 3. Edit and save README file 

In this step, you’ll go into the README file that was created in the previous step and edit it with some information. The README file is a Markdown file, as indicated by the .md extension. We’ll talk more about Markdown files later; for now, just treat it as a plain text file.

* From the top-level page of the repository (which you can navigate to by clicking the &lt;> Code tab), click on the name of the file, README.md
    * Now you should see a very short page, since the README file does not have content yet.
* To edit files, click on the pencil icon beside where it says “Raw” and “Blame”; you can also press E as a shortcut. 
* The README file is where you would give a description of your repository, who made it, what it’s for, and so on. You could also add a CC license here to indicate how you would wish to share your project. 
    * Here’s a demo of one that you can copy and paste for this workshop.
* Scroll to the bottom of the page where it says Commit changes. There are two comment boxes that can be filled in when committing changes. The short description is required–ideally, it contains a brief message about the changes you made to the file. An optional larger description box can be filled out, as well.

Go back to your published website page and reload it–it might take a minute but your page should now display the edited README file.

By default, GitHub Pages will use your README.md file as the homepage for your web page unless there is a file called index.md in the repository. We’ll be creating this index.md later in the workshop. 
