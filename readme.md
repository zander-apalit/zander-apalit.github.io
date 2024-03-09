---
layout: page
title: Read Me
permalink: /readme/
---
# HOW TO HOST A RESUME USING JEKYLL
---
### PURPOSE
The purpose of this readme page is to demonstrate hosting a resume using Github Pages. This process will make use of Jekyll to host the website, but it won't require any knowledge of Jekyll to complete. All of the editing can be done either through your Markdown editor or through Github Pages. This document additionally serves to demonstrate values present in Etter's _Modern Technical Writing_, namely the value of using a light markdown language, and the advantages of hosting a static website.

### PREREQUISITES
This process will require two things:
1. A resume formatted in Markdown. A guide to Markdown can be found in the **More Resources** section.
2. A Github account. [Create an account here if you don't have one.](https://github.com/)

### INSTRUCTIONS
##### 1. Fork the Jekyll Now repository to your own Github repository
When you fork a repository in Github, you create a copy of it in your own repository. You can then make edits without affecting the original page. You will be forking the Jekyll Now page, which is a Jekyll website template hosted on Github pages. By copying this repository, you can take advantage of the Jekyll template without having to learn Jekyll.
1. Navigate to the [Jekyll Now](https://github.com/barryclark/jekyll-now) repository.
2. Click on the **``Fork``** button in the top right corner.
3. Rename the repository to "**your-github-name-here**.github.io". It is important that you type your Github account name exactly.
You should now have a Jekyll template hosted on your own Github page. For the next step, navigate to your profile and click on the repository that you have just created.

##### 2. Adjust your repository settings
Before you configure your website, you'll have to adjust some settings.
1. Navigate to your website repository.
2. Click on the ``Settings`` button in the top middle of the page.
3. Click on the ``Pages`` section, found on the left under ``Code and automation``.
4. In the ``Branch`` section, adjust the dropdown box to **master**.
5. Click on the save button beside the dropdown box.

Your website is now ready for configuration!

##### 3. Configure your website
In this step, you'll adjust the appearance of your website to your liking.
1. Navigate to your website repository.
2. Click on the ``_config.yml`` file. This file is where you'll adjust various sections of your website.
3. Configure this file to your liking. Fields such as the website title, description, and social media links can be edited. Additional instructions are located within the file.
4. When you're satisfied with the configuration, click on the ``Commit changes`` button in the top right.
5. Click on the ``Commit changes`` button in the bottom right of the dialogue box that appears.

##### 4. Upload your resume to your website
Finally, it's time to upload your resume to your website.
1. Prepare your resume Markdown file so that it's ready for copying.
2. Navigate to your website repository
3. Click on the **``index.html``** file. This file constructs the landing page for your website.
4. Delete the all the contents of this file that are below this block:
   
```
---
layout: default
---
```

5. Copy and paste the contents of your resume Markdown file in place of the section you have just deleted.
6. Click on the ``Commit changes`` button in the top right.
7. Click on the ``Commit changes`` button in the bottom right of the dialogue box that appears.

Your resume should now be hosted on your website.

##### 5. Visit your website
Now that you've finished constructing your website, it's time to visit it.
1. In your web browser, navigate to the search bar.
2. Type in **your-github-name-here**.github.io and search.
3. You should now be visiting the website that you've hosted on Github pages. It is important to note that changes made to your website will take a few minutes to appear on the website.

Here is an example of my website that I've hosted on my Github account **zander-apalit**. You can see how I navigate to the website, and how it appears.

![Demonstration of navigating to a Jekyll website](https://github.com/zander-apalit/zander-apalit.github.io/blob/master/demo.gif)
    
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
