---
layout: post
title: "Shiny: The future in R web apps development"
date: 2012-12-13 16:52
comments: true
categories: [shiny, web, R]
---

### Web options for R 

The last service/server that I worked was _Opencpu_ and now, after play with shiny for a while, I could say: "It's really easy to use and well done!".

See more about shiny at:

{% blockquote Source http://www.rstudio.com/shiny/ RStudio - Shiny %}
Easy web applications in R

Shiny makes it super simple for R users like you to turn analyses into interactive web applications that anyone can use. Let your users choose input parameters using friendly controls like sliders, drop-downs, and text fields. Easily incorporate any number of outputs like plots, tables, and summaries.

No HTML or JavaScript knowledge is necessary. If you have some experience with R, you're just minutes away from combining the statistical power of R with the simplicity of a web page.
{% endblockquote %}

A toy package with some extensions and examples: {% github marcionicolau/shinyExt 4f89a7f6bd9c0566725fa315398d6db478013249 %}

```r
require(devtools)
install_github('shinyExt','marcionicolau')

require(shinyExt)
``` 

{% gist 4263949 %}
