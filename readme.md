
# How to Use This Repository
This repository contains the tools necessary to create three different data management documents; a documentation file(README), data implementation plan and an internal data sharing plan. We also provide the tools to turn any of these documents into a webpage for your project using Github Pages. We have created template and example documents for each document. as a lot of this walkthrough is designed to help set up a Github Pages webpage. The following steps contain links and instructions to help you through this process. After completing these steps you will have a data management plan and a working webpage for specific to your research project. If you are only interested in creating the actual and don't want to make a Github Webpage then skip to [this](#markdown-editing) step.
This document will help you
* [Understand Github](#github) and [Github Pages](#github-pages)
* [Cloning and Modifying Our Templates](#cloning-and-modifying-our-templates)
* [Basic Markdown Editing](#markdown-editing)
* [Customizing Github Pages](#customizing-github-pages)

## Github
Github is a website with variety of uses including: sharing data and creating collaborative projects. You will need a Github account if you want to use Github to publish your documents and can create one [here](hhttps://github.com/join "Create a Github account").
* Note: the url for the webpage will use either the username or organization name which sets it up. Try to make sure the URL will be appropriate to share with others and relevant to what is on the webpage.

There are two types of repositories on GitHub; public ones and private ones. Public repositories can be seen by and downloaded by anyone on the web but only edited by collaborators. Private repositories can only be seen by its contributors.  Normally Github charges for private repositories but researchers can apply for a free private account by following [these](https://help.github.com/articles/applying-for-an-academic-research-discount/ "Apply for an Free Private Academic Research Account") steps.

## Github Pages
Github Pages allows you to create webpages where Github provides hosting and a web domain name. This allows you to publish documents through GitHub that anyone can access through a web browser.

###### ------------** IMPORTANT NOTE ** ------------
GitHub Pages are **ALWAYS PUBLIC REGARDLESS OF THE PRIVACY OF THE REPOSITORY**. This combined with the fact that  **ALL FILES IN A PAGEs ENABLED REPOSITORY ARE VIEWABLE**  means you must be certain their is **ABSOLUTELY ZERO** private information in your repository before you set it up with Github Pages. You can decide which repositories in your account to publish using Github Pages with one exception; your **USERNAME.github.io** repository (which must be created for Github Pages to work with any of your repositories) will always be navigable and thus **public**. If there is some question about the privacy of files in your repository then it maybe best to simply create a new Github repository free of the private information to use with Pages.

### Setting Up Your Account to Use Github Pages
Setting up Github Pages is fairly simple and straight forward.
- First, in your browser, go to github.com and make sure you are logged into the account which will publish your documents.
- Then create a new repository with the name USERNAME.github.io (where the USERNAME is replaced with your username). I entered "landonma.github.io" since my username is landonma.
- You can now navigate to any files uploaded to this repository
- Any .md or .html files will appear as webpages while all other files will be navigable using their full file name  
**Note:** Github pages usually takes around **5-7 minutes** to upload new pages and edits

Next you will need to enable Github Pages on any other repositories such as the one that will host your various data management documents.
- To do, sign in to your account on Github.com
- Click on your user picture (upper right corner) and go to "Your repositories"
- Click on the repository you want to enable or create a new repository
- Under the name of the repository is a series of tabs, go to the "Settings" tab
- Below the Merge button and above Danger Zone is "GitHub Pages"
- Click the "source" drop down menu and select either master

## Cloning and Modifying Our Templates

Next clone or download [our repository](https://github.com/landonma/datamanagement "Data Management Implementation Plan Repository"). Then place upload the template file into your own repository. ([Here](https://help.github.com/articles/adding-a-file-to-a-repository/ "Adding a File to a Repository") is a quick article if you are unfamiliar with Github)

### How to edit the Templates




### How

## Markdown editing
Markdown was created to be easy to read and edit and we use this format for all the documents in this repository. Markdown files(.md) have some of the functionality of writing documents in an HTML format while still remaining easily readable. Github and Github Pages are set up to use Markdown already. The coding involved with formatting a Markdown document is easy to learn and you can find a guide for using markdown [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Markdown Cheatsheet"). Some additional tips for creating markdown documents:
* There must be a space after the ##'s when making headers
* There is NO space when bolding and using italics; ie. **bold** not ** bold **
* If you want to force a line break put two spaces at the end of the line then press Enter.
(ie. end of line." __ ")
* The guide shows the different ways to format hyperlinks but doesn't describe the different types of links. I describe the different links in other section [below](#customizing-github-pages).

It is easiest to edit markdown files either by editing the documents through Github in a web browser or by using source code editing software such as Notepad++ or Atom (these docs were created using Atom). You could theoretically use Microsoft Word or Google Docs but it is strongly recommended that you use Github's editor instead. To edit them using Github simply navigate to your repository, click on the file you want to edit and click the edit (pencil) button on the top right of the page.

## Using Our Template and Guide Documents
The template markdown file (found [here](datastorage-norm-edited.md)) is meant to be edited and filled out directly. As you look through the template file you should fill in any _____ spaces and change any of the boiler-plate text with details specific for your project.  

The guidance document (found [here](guidance-edit.md)) is meant to help you think about the important parts of each section and is **not** meant to be edited and published. This document will help illustrate what is important to include and consider in each section.

## Customizing Github Pages
When you use Github Pages your repository is your webserver. Therefor, the file titled "index" will be the homepage of your website. For the repository we created that page is the one you are reading right now. For your repository you will want something that suites your needs.

If the only page you want is the data management implementation plan document you can rename that document "index.md". Now whenever you navigate to your repository URL you will get document.
You may want a list of links with some basic text for the home page. To do this, use this markdown file as a template and edit the text and links as necessary. There are three types of links used in this repository and they all have slightly different text inside the parentheses " () ". To best distinguish between these types it is best to look at the code in an editor.

* Some of them are basic hyper links which contain the full url of the page in the () which is linked to ie. [google.com](google.com).
* Others are relative links which match a file name in your repository. To create this type of link include the full file name exactly as it appears in the repositry including the extension. [Data Management Implementation Plan Template](datastorage-norm-edited.md). All the links that point to other pages in this repository were created using relative links so if you have all the file names as this repository then your wont have to change any of these links (but may need to delete ones such as the link to the guidance file).
* There are also "links" which jump to header within the same page. These are used in the table of contents [this](#customizing-github-pages). They are created by putting one "#" then the name of the header you wan to jump. The header name must be typed in all lower case even if the actually header isn't and the spaces are replaces with dashes -. Make sure to change these links whenever a header name is changed. Also note that there should only be **ONE #** regardless of the header level.


Github has also created a number of themes that change the appearance of your pages and can be viewed [here](http://jekyllthemes.org/ "Available Themes").  Instructions on how to apply the themes are [here](https://help.github.com/articles/adding-a-jekyll-theme-to-your-github-pages-site/ "Add Jekyll Themes"). This repository has **no theme** applied to it but you are welcome to try them out.
* I suggest the method that edits the "_ config" file because you can simply delete the line if you want to remove the theme later.

You can also use HTML to create/format any pages on your repository. For simplicity and to show what Markdown can do; nothing in this repository was written using HTML.
