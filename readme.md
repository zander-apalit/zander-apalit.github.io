---
layout: page
title: Read Me
permalink: /readme/
---

# HOW TO HOST A RESUME USING JEKYLL
---
### PURPOSE
The purpose of this readme page is to demonstrate hosting a resume using Github Pages. This process will make us of Jekyll to host the website, but it won't require any knowledge of Jekyll to complete. All of the editing can be done either through your Markdown editor or through Github Pages.

### PREREQUISITES
This process will require two things:
1. A resume formatted in Markdown. A guide to Markdown can be found in [More Resources](#-More-Resources)
2. A Github account. [Create an account here if you don't have one.](https://github.com/)

### INSTRUCTIONS

### MORE RESOURCES
Some helpful resources related to resume hosting on Jekyll:
- Andrew Etter's [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS), which discusses the modern approaches to technical writing, and the value of hosting a static website.
- [Markdown Tutorial](https://www.markdowntutorial.com/), which walks you through rudimentary features of Markdown.
- [Dillinger](https://dillinger.io/), an online Markdown editor.
- [Introduction to Jekyll](https://ubc-library-rc.github.io/intro-jekyll/jekyll/), which describes the process of hosting a website on Github pages using Jekyll.

### AUTHORS AND ACKNOWLEDGEMENTS
Thank you to Barry Clark for his [Jekyll Now](https://github.com/barryclark/jekyll-now) repository used in this tutorial.
Thank you to my group mates Seyi Asoga and Anmolpreet Singh for their feedback and assistance.

### FAQ

##### Why should I host my resume on a static website?
As described in Etter's _Modern Technical Writing_, hosting your content on a static website has many advantages in distribution. Any time the content is updated, the changes are immediately available to anyone accessing the website. If you were distributing your files by email, for example, there would be outdated versions of your content floating around, and everytime you updated the content, you would have to redistribute it to every relevant person in a very inefficient process. Static websites ensure there is always one definitive and up-to-date version of your content that is widely accessible.

##### Why is my resume not showing up?
Updates to your Github Page aren't immediate and make take a few minutes to show on the website after updating. If after waiting, your resume still isn't appearing, ensure that you have placed the contents of your resume in the proper location in your Github repository. Your resume should be located in **``index.md``** (_which you should have renamed from index.html_). Verify that your resume has been properly copied into the **``index.md``** file; the file should begin with the layout block followed by the contents of your resume Markdown file, copy and pasted from the source. Ensure that the resume has retained it's formatting from the original Markdown file. Lastly, make sure your file is saved in the repository as **``index.md``** and not **``index.html``**, otherwise it will not display properly.
