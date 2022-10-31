---
layout: default
title: Create a GitHub Repository
nav_order: 6
parent: GitHub Introduction
---

## 1. Create a new GitHub repository

1
{: .label .label-step}
Ensure you have created a GitHub account and are logged in.
{: .step}

2
{: .label .label-step}
From your GitHub main page, click on the plus icon, followed by the New Repository button.
{: .step}

3
{: .label .label-step}
Provide a name for your repository. This name will be part of the URL of your repository as well as part of the address of your published website, unless you choose a custom domain.
The repository URL will take the form: https://github.com/<your-github-username>/<your-repo-name>
{: .step}

4
{: .label .label-step}
Check the box to Initialize this repository with a README. 
{: .step}

Your README file is a plain text file (same as a .txt file) that typically contains descriptive information about your repository (Who made it? What does it contain? What is it for?, etc.). You can also add a README file later if you like.
{: .note}

5
{: .label .label-step}
Click the Create repository button. 
{: .step}

6
{: .label .label-step}
Your browser will now open to the top-level page of the repository. Your repository will contain one file: README.md.
{: .step}


## 2. Set up GitHub Pages 

In this step, you will enable the GitHub Pages feature in your repository settings. GitHub Pages knits together your repository files and turns them into an HTML site. You can do this at any stage of your project. Turning the feature on will allow you to view the public version of your website; note, however, that the website will also be published for others to see.

1
{: .label .label-step}
Open the Settings Tab in your repository.
{: .step}

2
{: .label .label-step}
Scroll down to the GitHub Pages section.
{: .step}

3
{: .label .label-step}
For the Source, set Branch:main and set the folder to /(root) and click Save. This directs GitHub pages to the top-level of your repository for your website content.
{: .step}

4
{: .label .label-step}
After a while, you should see a link to your website appear in the GitHub Pages section. That link is now live.
NOTE: You may initially receive a 404 error as the website is being built.
{: .step}

Your website will look pretty empty at this stage. Keep this tab open so when you make changes in this workshop, you can refresh the page and view your changes.

## 3. Edit and save README file 

In this step, you’ll go into the README file that was created in the previous step and add some text. The README file is a Markdown file, as indicated by the .md extension. We’ll talk more about Markdown files later; for now, just treat it as a plain text file.

1
{: .label .label-step}
From the top-level page of the repository (which you can navigate to by clicking the &lt;> Code tab), click on the name of the file, README.md. 
{: .step}

2
{: .label .label-step}
To edit files, click on the pencil icon beside where it says “Raw” and “Blame”; you can also press E as a shortcut.
{: .step}

3
{: .label .label-step}
The README file is where you would give a description of your repository. You could also add a CC license here to indicate how you wish to share your project. For this activity, copy and paste the following text to your README file.
{: .step}

```
This work is licensed under a Creative Commons Attribution 4.0 International License.
```
  
4
{: .label .label-step}
Scroll to the bottom of the page where it says Commit changes. There are two comment boxes that can be filled in when committing changes. The short description is required: a brief message about the changes you made to the file. An optional larger description box can be filled out, as well.
{: .step}

5
{: .label .label-step}
Put "add license info" in the short commit box. Click on the green Commit button.
{: .step}
  
6
{: .label .label-step}
Go back to your published website page and reload it–-it might take a minute but your page should now display the edited README file.
{: .step}

By default, GitHub Pages will use your README.md file as the homepage for your web page **unless** there is a file called **index.md** in the repository. We’ll be creating this index.md later in the workshop. 
