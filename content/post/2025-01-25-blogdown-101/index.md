---
title: blogdown 101
author: chlee
date: '2025-01-25'
tags:
  - hugo blox
  - blogdown
slug: blogdown-101
output:
  html_document:
    toc: yes
    number_sections: yes
---



``` r
seq(1,10,1)
```

```
##  [1]  1  2  3  4  5  6  7  8  9 10
```


library(devtools)
remotes::install_github('rstudio/blogdown')
library(blogdown)

imstatsbee/archive
new_site(theme="HugoBlox/theme-academic-cv")

blogdown::serve_site()
blogdown::stop_server()
rmdir -rf ./content/post/2020-01-r-markdown

blogdown::new_post(title="How to use blogdown in 2025")
blogdown::new_post("my new post", ext=".Rmd")

blogdown::build_site()
blogdown::check_site()

usethis::use_git()

https://imstatsbee.netlify.app


https://bookdown.org/yihui/blogdown/
https://github.com/HugoBlox/theme-academic-cv

Q. main page ./content/authors/admin/_index.md

# References {-}

https://zihangwang.org/2024-02-12-how-to-use-blogdown-in-2024/
https://www.kirenz.com/blog/posts/2019-07-20-up-and-running-with-blogdown/
https://www.shilaan.com/post/building-your-website-using-r-blogdown/
