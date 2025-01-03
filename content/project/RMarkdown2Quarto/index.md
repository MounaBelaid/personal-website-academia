---
date: "2024-04-01T00:00:00Z"
title: "{RMarkdown2Quarto} Shiny App for Switching to Quarto"
external_link: 
tags:
- Shiny Applications
image: 
  caption: 
  focal_point: Smart
links:
- icon: mastodon
  icon_pack: fab
  name: Follow
  url: https://mastodon.social/@mouna_belaid
summary: ""

url_code: 
url_pdf: 
url_slides: ""
url_video: ""
---

Are you thinking about a shift to Quarto? With the [{RMarkdown2Quarto}](https://mounaabelaid.shinyapps.io/RMarkdown2Quarto/) Shiny application, you can switch quickly and start to improve your work quality. 
It's a Shiny application that ensures you make the right choice without any doubt. The web application aims to convert RMarkdown documents 
into Quarto documents. 
The conversion process involves locating a list of available RMarkdown files within a user-specified folder and subsequently transforming 
the Rmd syntax format to qmd format in the front matter. The user can also choose a folder from which only .Rmd files will be selected if 
the application runs locally. If you don't have an Rmd file on hand, you can export the demo RMarkdown file and import it to test the application. This application also aims to facilitate the conversion of RMarkdown files to Quarto files by converting the in-header chunk option syntax to the in-body syntax in the .qmd converted available files. 
I used the bslib, ShinyFiles, and ShinyAce packages for my tech stack.
