---
layout: post
title: R Markdown Tips and Tricks
---

**Figuring out how to make your Rmarkdown website (or document) look pretty is something that I have spent a long time struggling with. Here is a list of some tips and tricks I have come across in my travels...** 

*First of all, see [this](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf) cheatsheet; the things I'm covering here are those not listed on this cheatsheet*

Additionally, [this](https://bookdown.org/yihui/rmarkdown/rmarkdown-site.html), specifically section 10.5 is an AMAZING resource for what you can do with an R Markdown site. 

**Change size of image**

This one is tricky, Rmarkdown does not like this.

![](/img/tt_1.JPG)

Within your header you can also control the figure width and height, although this means all figures will be rendered the same size in your document:

![](/img/tt_2.JPG)


**Center your text/photos**

![](/img/tt_3.5.JPG)

**Add breaks**

![](/img/tt_4.JPG)

**Adding Table of Contents (TOC)**

TOCs need to be added in your header. You can make the tocs float (follow you as you scroll down the page) or remain at the top of the page. 

![](/img/tt_5.JPG)

**Adding Tabs** 

To control the appearance of tabs you can use .tabset-fade (which causes tabs to fade in and out when switching between tabs) and .tabset-pills (which looks more like a button than a tab)

![](/img/tt_6.JPG)

![](/img/tt_9.JPG)

Here is the same tabs with .tabset-pills

![](/img/tt_10.JPG)

**Themes**

There a few different themes you can use for a simple R Markdown website or document. The theme needs to be included in the header.
Themes already installed in your RStudio include: "cerulean”, “cosmo”, “flatly”, “journal”, “lumen”, “paper”, “readable”, “sandstone”, “simplex”, “spacelab”, “united”, and “yeti”. 

[Here](http://www.datadreaming.org/post/r-markdown-theme-gallery/) is a good website to look at a screen shot of each theme.

There are several add-on R packages that you can install to implement even more R Markdown HTML themes. For example `prettydoc`, `rmdformats`, `hrbrthemes`, `tufte`, and `tint`. See the website link above for screenshots of those themes.

How did I make those words appear in R code? 

![](/img/tt_7.JPG)

**Handy code for embedding a PDF**

I use this handy piece of CSS code (thanks John Mola!) on my own website for embedding my CV. Notice here R is looking for a folder called "pdf"

![](/img/tt_8.JPG)

My main advice for making your Rmarkdown document or website look the way you want it to is "take to the internet!" There are many, many resources out there (the least of which is diving into the code of the websites you admire) and I have the links to a few at the top of this post. Happy formatting!

