---
layout: page
title: Introduction to R Markdown
visible: true
tags:
  # languages
  - R
  # levels
  - beginner
---
<!-- change visible to true if you want it on the site -->

 - **Author**: [Dr. Sophie Shaw](https://github.com/SophieS9) 
 - **Research field**: Bioinformatician working on analysis of Next Generation Sequencing Data

# Introduction to R Markdown
It's important during research to keep a thorough record of your analysis. This is a common practice within the wet lab with all researchers keeping a lab book. However when it comes statistics and plots, people are less cautious about recording what they have done. R has several nice ways to record your activites, and to make these as reproducible as possible including R Scripts and R Markdown. As a researcher who uses R on a daily basis, I started out using R Scripts to record my research. However, I've often found myself lost in a 1000 line script, trying to work out what each line of script is doing and what plots are produced. Even with thorough notation of the script, this can often still be confusing. R Markdown is a nice solution to this situation, allowing you to group your code into "chunks" as well as acting like a notebook, with plots pictured directly below the code. It also has the ability to the render the R Markdown into easy-to-read documents including PDF, html or word document formats, allowing for easy production of reports.

This workshop has been largely inspired by the fantastic resources available at the [R Markdown Website](http://rmarkdown.rstudio.com/index.html).

## What is Markdown and R Markdown?
Markdown is a coding language that allows for text-to-HTML conversion. It was originally designed for web developers to allow for editing of web pages with an easy-to-read and easy-to-write plain text format. This webpage has been written in Markdown and then github has rendered this to allow you to view it as a webpage. You can see the original Markdown code [here](https://raw.githubusercontent.com/SophieS9/SG-RMarkdown-Intro/master/Intro_RMarkdown.md). Due to it's basic nature, you need none to very little programming knowledge in order to write in Markdown! 

R Markdown is a variation on Markdown allowing it to be implemented in R. This [video](https://vimeo.com/177254549) gives a great, short explanation of R Markdown.

## Using R Markdown in RStudio
The benefits of R Markdown are best appreciated when using it within RStudio. If you don't already have RStudio, you can download it from the following [link](https://www.rstudio.com/products/rstudio/download/). 

RStudio is an easy to use graphical user interface for running R. It allows you to view scripts, the console, your environment and plots all within one window. For more details on this, see our workshop on [Version Control with RStudio and Github[https://aberdeenstudygroup.github.io/studyGroup/lessons/SG-T1-GitHubVersionControl/VersionControl/].

Once RStudio is installed and running, your window should look something like this:

INSERT SCREENSHOT

As well as installing RStudio, you'll need to have the package for rmarkdown installed. To do this, in the console panel, run:
```
install.packages("rmarkdown")
```

You should now be able to open a new R Markdown file. To do this go to the "Open" symbol in the top left hand corner and select "R Markdown"

<p align=center>
<img src="./Images/Open_Markdown.png">
</p>

## Code Blocks and Plots

## Formatting

## Inserting Images
 
## Inserting Citations

## Rendering R Markdown into Documents
