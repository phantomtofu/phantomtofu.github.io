---
id: 1
title: "How did this happen?"
subtitle: "Publishing a simple website"
date: "2023.09.26"
tags: "git, web"
---

So, I had heard that one could host a static webpage with GitHub. I've built static webpages before! In school... They used iframes based on tutorials from w3schools. 

I kinda started to do this about a year ago and forgot. All I had done was a readme with the text "trying to make a webpage." Well, I have a new tool now - modern medicine! (ADHD diagnosis and Adderall). 

The Pages setting in the repository has a handy link to add a Jekyll theme https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll. Just fork a repository, install Ruby, pick a theme, wait install Ruby? I got pretty mixed up in the instructions - turns out I probably didn't need to test it locally anyway (on Windows, which complicates things). Oh well, I gave up to try to find something simpler. 

After searching some themes and templates, I found a similar path that worked out. The handmade-blog from parksb has pretty simple instructions and is published as a template. Without rehasing the readme too much, here's how it worked for me:

1. Use the template (all branches), named as [github user].github.io
2. Clone to editor of choice (VS Code)
3. Discover that running and building requires NPM (Javascript stuff I've never done), which requires Linux(?)
4. Install WSL, and the VS Code extension
5. Install NPM in WSL
6. Connect VS Code to WSL using extension, and clone again (also delete the repository from Windows)
7. Edit -> npm build -> npm start -> runs on a local web server for review -> repeat
8. Publish by committing and pushing(? still unclear on git terminology). I haven't actually tested this step at time of writing. 

After I publish this article, it's time to work on the rest of the site. 


![https://www.youtube.com/@billwurtz](/images/hdth.png)
