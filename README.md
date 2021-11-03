# A Tutorial On Hosting A Resume on GitHub Pages
The purpose of this README is to show how you can host and format your resume using several tools such as Jekyll, Markdown, and GitHub Pages. This README will also mention Andrew Etter's general principles of Technical Writing from his book, [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS), which you can use to improve your own technical writing.

## Prerequisites

This project will require:
- **A personal GitHub account** 
- **A Markdown formatted resume**

  - GFM also known as GitHub Flavoured Markdown is one option. See [additional resources](https://github.com/itobinpe/itobinpe.github.io/blob/main/README.md#additional-resources) for more information.

- **A Markdown editor**

    Options include:
    - Visual Studio Code 
    - Atom
    - Vim 
- **Jekyll or your choice of a static site generator**

    - See [additional resources](https://github.com/itobinpe/itobinpe.github.io/blob/main/README.md#additional-resources) for a guide on installing Jekyll.

## Guide

These steps will follow Etter's general principles on Technical Writing and will guide you through the process of hosting your resume on GitHub pages.

### **Step 1. Creating the resume**

Markdown is one of the most widely used lightweight markup language. Etter suggests to use a good text editor along with different flavours of Markdown for their own individual features.
1. Choose any Markdown editor to use for your resume.
2. Create and format your resume using one of the available Markdown flavours such as GitHub Flavoured Markdown.
    
    - See [additional resources](https://github.com/itobinpe/itobinpe.github.io/blob/main/README.md#additional-resources) for a tutorial on GFM.
3. Save and name the resume as `index.md`

### **Step 2. Creating the repository**

As mentioned in Etter's book, Etter recommends using a Distributed Version Control System (DVCS) to work on technical writing because developers prefer them. DVCS have better performance, allows the ability to do offline work and it is one of the best ways to collaborate with other people on the same file concurrently. GitHub is one example of a DVCS.

1. Create and login to your GitHub account. To create an account, follow these [steps](https://github.com/join).
2. Once you have logged in, click on the "+" icon at the top right near your profile picture. In the dropdown menu, click on "New repository".
3. Type `<username>.github.io` in the repository name and replace `<username>` with your GitHub username.

    - An example with the username `test999`. The owner would be `test999` / `test999.github.io` in the repository name.
4. Skip the additional description, leave the permissions to public, and you can also skip the last three checkboxes. 
5. At the bottom of the page, click the green "Create Repository" box.

### **Step 3. Uploading the resume**
1. Click on the "uploading an existing file" highlighted in blue, below `HTTPS|SSH`.
2. Click on the "choose your files" option that pops up or drag your resume file in the box.
3. Select your resume file if you pressed the "choose your files option" otherwise, skip this step.
4. At the bottom left side, click on the green "Commit changes" box.

### **Step 4. Using Jekyll themes**
Jekyll is a static site generator which makes it easy to format and customize your site. Etter recommends using static site generators to make something more complex with content and a theme. Also, Etter prefers static sites over dynamic sites because you can host them anywhere, even offline on your local computer. Static sites are fast, simple, portable and secure.

1. On your repository's main page, click on settings at the right hand side.
2. At the left, click on "Pages" in the list.
3. Click the "Choose a theme" button and it should redirect you to a page where you can select a theme for your site.
4. Once you have selected your theme, click on the green "Select theme" box.
5. The site should now be published as mentioned in the green box. Click on the link to go to your site.

### **Conclusion**
It may take some time to update, but your Markdown formatted resume should be visible on GitHub Pages with your choice of a Jekyll theme.

#

## Additional Resources
- What is [Markdown](https://www.markdownguide.org/getting-started/)?
- A simple [tutorial](https://www.markdowntutorial.com/) for Markdown.
- A [tutorial](https://guides.github.com/features/mastering-markdown/) on GitHub Flavoured Markdown.
- The [documentation](https://jekyllrb.com/docs/) to install Jekyll.
- The [documentation](https://jekyllrb.com/docs/configuration/) to configure Jekyll (`_config.yml`).
- Andrew Etter's [book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS), Modern Technical Writing.

## Frequently Asked Questions

1. Why is Markdown better than a word processor?

    - Markdown is lightweight markup language that is very easy to learn than other word processors. In version control, it is very difficult to merge changes when you are working with different people while using a word processor. With Markdown, this is very simple to merge with, which makes it an easier format to collaborate with others. 

2. Why is my resume not showing up correctly or at all?

    - Using this guide, a resume may not show up if it's titled differently than `index.md`. This is because `index.md` serves as the root of the site and it is the first thing that it will show. 
    - A resume may not show up correctly if it's not properly formatted in Markdown (see [additional resources](https://github.com/itobinpe/itobinpe.github.io/blob/main/README.md#additional-resources) for more information). It could also be showing incorrectly if there's something wrong with the `_config.yml` file. This file should be generated correctly upon creation. See [additional resources](https://github.com/itobinpe/itobinpe.github.io/blob/main/README.md#additional-resources) for the documentation of `_config.yml` file.

## Acknowledgements
Author: **Ian Tobinpe** 
  
**Editors**:
- Andrea Abellera
- Megan Galbraith
- Matthew Kwiatkowski
- Andrii Provozin

 **Jekyll Template:** [Slate by parkr](https://github.com/pages-themes/slate)  
