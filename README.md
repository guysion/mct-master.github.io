# mct-master.github.io

The blog of MCT: [https://mct-master.github.io](https://mct-master.github.io)

## Jekyll

We are using [Jekyll](https://jekyllrb.com/), here's a list of tutorials that might be useful to get familiar with the GitHub and Jekyll environments:

* [Using GitHub to Create and Host a Personal Website](http://jmcglone.com/notes/2014/05/03/using-github-to-create-and-host-a-personal-website)
* [Creating and Hosting a Personal Site on GitHub](http://jmcglone.com/guides/github-pages/)
* [Quick Start Guide with Jekyll](https://jekyllrb.com/docs/quickstart/)

To edit the site you have to contribute your changes (e.g., posts) to this source code repository. After your changes are committed and merged to the master branch, Github will automatically rebuild the static site and make it instantly available to the public. Note that editing existing contents and adding new contents can be all done directly from the Github web interface. It is therefore not strictly needed to clone the repository and install the required software to edit the site locally. [Here](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/) you can find instructions for setting up a local copy of a Github Pages site.

The content of the site is released under [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/).

## Markdown

[Markdown](https://en.wikipedia.org/wiki/Markdown) is a markup language with plain text formatting syntax. It is mainly designed so that it can be converted Hypertext Markup Language (HTML), the standard markup language for creating web pages and web applications. It has been basically designed for those who want to avoid to write in HTML, it is designed for humans!

* A useful Markdown cheatsheet can be found [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
* A table showing how the Markdown syntax is converted to HTML can be found [here](https://en.wikipedia.org/wiki/Markdown#Example).

There exist a number of Markdown editors, so it is easy to see a rendered version (how it will look like on the browser/web):

* [MacDown](https://macdown.uranusjr.com/): Mac
* [Typora](https://typora.io/): Mac, Windows, Linux
* [Haroopad](http://pad.haroopress.com/): Mac, Windows, Linux
* [ghostwriter](https://wereturtle.github.io/ghostwriter/): Windows, Linux

And a more complete list can be found [here](https://alternativeto.net/software/macdown/).


## Before uploading images...

It is important to optimize the size of an image (typically around or below 100 KB) before uploading it to the web, what is known as image optimization for the web. A handy tutorial on how to optimize images for the web on Gimp (which is a free software) can be found [here](https://smallbusiness.chron.com/optimize-images-gimp-45437.html). You can also use other image editors, such as Photoshop. It is important to optimize the images before uploading it to the online directory in order to provide a smooth experience to the users! It is also important to add at least one image to complement the text with   visual information and make it more interesting to the reader!

Please note that the names of the image files should not contain white spaces to avoid potential issues of systems not finding the image.

## Instructions for contributing to the MCT site

### Posting blog posts

You can add a blog post by creating a file in the [_posts](https://github.com/MCT-master/mct-master.github.io/tree/master/_posts) folder of this repository.
Note that you can directly create the file from the Github web interface by navigating to the [_posts](https://github.com/MCT-master/mct-master.github.io/tree/master/_posts) folder and clicking on the **New file** button.

The file must be markdown formatted and must include a number of metadata fields at the top of the page, which is done in a YAML front matter (see example below).

In order to let the system organize the blog posts automatically by chronological order, it must be named as `YYYY-MM-DD-short-version-of-title.md` (YYYY-MM-DD being the publication date).

These are the available categories that can be used:

* Audio-Programming
* DSP
* HCI
* Motion-Tracking
* Physical-Computing
* Portal
* Projects
* Sonification

The first image used in the blog post can be used to appear in the homepage. This should be defined as `image: /assets/img/name-of-file.jpg`

Finally, the use of a short excerpt is encouraged to control the text that should appear in the homepage: `excerpt: "A short summary, typically copy-pasting the first paragraph of the blog post."`

Once the file is completed, it can be saved and committed to the `master` branch (Github web interface will do it for you upon saving the newly created file). Then, it will automatically be added to the news section (it may take a few seconds).

Required structure of the markdown file for a news post:

```markdown
---
layout: post
title: "Welcome to Jekyll!"
date: 2018-08-21 10:10:42 +0200
categories: Portal
author: Name Surname
image: /assets/img/name-of-file.jpg
excerpt: "A short summary, typically copy-pasting the first paragraph of the blog post."
---

Add the post body here using markdown syntax.
```

Check [Github's markdown syntax guide](https://guides.github.com/features/mastering-markdown/) for examples on how to format text with markdown.

Existing news entries can also be easily edited by navigating to the file with the Github web interface and clicking on **Edit this file** (i.e., the icon with a pencil). When changes are committed to the `master` branch the post will be automatically updated on the site.

Images and other assets (e.g. css, video files (with a reasonable size), pdf files, javascript files) can be organized in the [assets folder](https://github.com/MCT-master/mct-master.github.io/tree/master/assets).

## Inspirational examples of similar masters

* https://www.smc.aau.dk
* https://www.upf.edu/web/smc
* http://www.gtcmt.gatech.edu
* http://ied17.rca.ac.uk

## Inspirational examples of blogs

* https://rcaied.tumblr.com: Here's an example of a mostly visual blog from a master (master in information experience design from RCA).

* http://womeninmusictech.gatech.edu: A blog built in Wordpress of multiple authors (the newsletter of Women in Music Tech at Georgia Tech).
* https://midassblog.wordpress.com: A blog built in Wordpress of multiple authors (the blog of the research project MIDAS).
