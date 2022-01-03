---
title: Reference & Resources
nav: Resources
---

### R and RStudio resources
- [R Reference Card by Tom Short](https://cran.r-project.org/doc/contrib/Short-refcard.pdf) 
- [Quick-R](https://www.statmethods.net/): quick reference for learning R
- [BasicBasics](https://rladiessydney.org/courses/ryouwithme/01-basicbasics-0/): step-by-step guide to installing and using R for new users
- [R for Data Science](https://r4ds.had.co.nz/index.html): an electronic book for many useful information about R
- [RStudio Cheatsheets](https://www.rstudio.com/resources/cheatsheets/): useful R cheat sheets with the most widely used commands.
- [stackoverflow](https://stackoverflow.com/)if you google your problem, it will often take you here. Someone may have already asked your question and many people have answered the question in many different ways with useful tips. Take advantage of this!

### R Markdown resources
- [Markdown Basics](https://rmarkdown.rstudio.com/authoring_basics.html): quick references to the most commonly used R Markdown syntax
- [Pandoc Markdown](https://pandoc.org/MANUAL.html#pandocs-markdown): Markdown syntax
- [rmarkdown.rstudio.com](https://rmarkdown.rstudio.com/lesson-1.html): Great overview for R Markdown basics. I strongly recommend to take a look!
- [R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/) This book is a free online version of [Chapman & Hall/CRC](https://www.routledge.com/R-Markdown-The-Definitive-Guide/Xie-Allaire-Grolemund/p/book/9781138359338). This online book contains almost everything about R Markdown. You will find this very useful.

### R graphics resources
- [Quick-R](https://www.statmethods.net/graphs/index.html)
- [The R graph gallery](https://www.r-graph-gallery.com/index.html)
- [ggplot2](https://ggplot2.tidyverse.org/)
- [ggplot2: elegent graphics for data analysis](https://ggplot2-book.org/index.html)
- [ggpubr](http://www.sthda.com/english/articles/24-ggpubr-publication-ready-plots/81-ggplot2-easy-way-to-mix-multiple-graphs-on-the-same-page/)
- [ComplexHeatmap](https://jokergoo.github.io/ComplexHeatmap-reference/book/)
- [Top R color palettes](https://www.datanovia.com/en/blog/top-r-color-palettes-to-know-for-great-data-visualization/)
- [Comprehensive list of color palettes in r](https://github.com/EmilHvitfeldt/r-color-palettes)
- [Introduction to Data Science - Chapter7. ggplot2](https://rafalab.github.io/dsbook/ggplot2.html#geometries): discusses the components of a ggplot2 graph in details and provides great examples.


To learn about using `workshop-template-b`, the content pages of this demo provide documentation and examples (also check the [README](https://github.com/evanwill/workshop-template-b/blob/master/README.md)).

Workshop sites using this template:

- [Demo](https://evanwill.github.io/workshop-template-b/) (this repository)
- [Go Go GitHub Pages (v.2)](https://evanwill.github.io/go-go-ghpages-b/) (workshop)
- [Get Started with OpenRefine](https://evanwill.github.io/openrefine-b/) (workshop)
- [Web Crash Course](https://evanwill.github.io/web-crash-course/) (workshop)
- [write-md: Markdown and Pandoc for Academic Writing](https://evanwill.github.io/write-md/) (workshop)
- [web-cites: Web Archiving to Fight Link Rot and Preserve Your Citations](https://evanwill.github.io/web-cites/) (workshop)
- [Hey API!](https://evanwill.github.io/hey-api/) (workshop)
- [Web Crash Course](https://evanwill.github.io/web-crash-course/) (workshop)
- [Try Linux!](https://evanwill.github.io/try-linux/) (workshop)
- [Make OER!](https://evanwill.github.io/make-oer/) (presentation)
- [Teaching Tech Hands-on](https://evanwill.github.io/tech-hands-on/) (presentation)

Other workshop sites an [minimal version of this template](https://github.com/evanwill/workshop-template) (no bootstrap):

- [get-git](https://evanwill.github.io/get-git/)
- [hello-arduino](https://evanwill.github.io/hello-arduino/)
- [clean-your-data](https://evanwill.github.io/clean-your-data/)
- [go-go gh-pages](https://evanwill.github.io/go-go-ghpages/)
- [Make @ the MILL](https://uidaholib.github.io/make-at-the-mill/)

If you need a Bootstrap 4 version, see older [v1.0 release](https://github.com/evanwill/workshop-template-b/releases/tag/v1.0). 

# Reference

## Git & GitHub

[GitHub](https://github.com/) is a popular web service for hosting Git repositories--with benefits!
It provides a handy web interface for editing and collaborating on repos, as well as, built in project management features and [free static web hosting](https://pages.github.com/) powered by [Jekyll](https://jekyllrb.com/).
Accounts are free.
To learn more check out Hello World on [GitHub Guides](https://guides.github.com/) or [GitHub Learning Lab](https://lab.github.com/).

## Markdown

[Markdown](https://daringfireball.net/projects/markdown/) is a standard to simplify writing content for the web. 
Markdown can be used any where on GitHub and in Jekyll.

- [Mastering Markdown GitHub Guide](https://guides.github.com/features/mastering-markdown/){:target="_blank" rel="noopener"}
- [GitHub Markdown documentation](https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax){:target="_blank" rel="noopener"}
- [Markdown in a Minute](https://evanwill.github.io/_drafts/notes/markdown-minute.html)

## Bootstrap 5

[Bootstrap](https://getbootstrap.com/) is a CSS framework designed to streamline developing user interfaces for your website.

[Bootstrap Icons](https://icons.getbootstrap.com/) are SVG-based icon set used to add graphics to your content.

## YAML

[YAML](http://www.yaml.org/) is a human readable plain text data format.
It is used in Jekyll for configuration, site data, and front matter.
Jekyll projects are [configured](https://jekyllrb.com/docs/configuration/) using the "_config.yml" file.

## Liquid

[Liquid](http://shopify.github.io/liquid/) is a flexible template language.
[In Jekyll]((https://jekyllrb.com/docs/liquid/) it allows you to layout pages built from modular components and data, using the "_includes", "_layouts", and "_data" directories.
Liquid includes features such as operators, loops, and filters to manipulate raw content. 
Liquid statements are enclosed by {% raw %}`{%  %}`{% endraw %} and variables in {% raw %}`{{  }}`{% endraw %}.

## Sass  

[Sass](http://sass-lang.com/) is a CSS extension / preprocessor. 
All normal CSS is valid SCSS, but Sass adds many powerful functions and programmatic features. 
Writing SCSS is often easier and more sensible, for example by supporting nesting, variables, and operators. 
Jekyll lets you write SASS in modular chucks called partials, in the "_sass" directory, that will be combined and compiled into normal CSS files when the site is built.
