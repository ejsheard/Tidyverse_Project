Tidyverse test project
================
Emma Jane Sheard
8 July 2021

## R Markdown

This is an R Markdown document. This is an R Notebook. You can use it to take notes and run code. For example, you can write your name on the line below. Try it:

Emma

``` r
# You can write code in chunks that look like this.
# This chunk uses some code from base R to plot a data set.
# To run the code click the Green play (triangle) button to the right. Try it!
plot(cars)
```

![](Tidyverse_Project_files/figure-markdown_github/unnamed-chunk-1-1.png)

Good job! The results of a code chunk will appear beneath the chunk. You can click the x above the results to make them go away, but let's not do that.

You can open a new R Notebook by going to **File &gt; New File &gt; R Notebook**. Note that R Notebook and R Markdown files are very similar... The main difference I can tell is that Notebook allows you to preview your document before you knit it. I'm more familiar with Markdown which requires you to knit the document to view.

# Adding chunks

To add a new chunk, press *Cmd+Option+I* (*Ctrl+Alt+I* on Windows), or click the *Insert* button at the top of this document, then select *R*. Try making a code chunk below:

``` r
print("Hello world")
```

    ## [1] "Hello world"

Good job! For now, you should place all of your R code inside of code chunks.

``` r
# You can click the downward facing arrow (grey) to the left of the green play (triangle) button to run
# every chunk above the current code chunk. This is useful if the code in your
# chunk depends on the code in previous chunks. For example, if you use an
# object or data set made in a previous chunk.
```

# HTML version

When you save the notebook, an HTML file containing the code and output will be saved alongside it. This makes a nice, polished report of your work to share.

Click the *Preview* button at the top of this document or press *Cmd+Shift+K* (*Ctrl+Shift+K* on Windows) to preview the HTML file. Try clicking *Preview* now.

**Note that: Preview does not work in R Markdown file. Notebook is probably better for larger documents when you want to check without knitting first**

# Packages

You can immediately run any function from base R within a notebook, But if you'd like to run a function that comes in an R package, you will need to first load the package in the notebook.

Do you remember how to run the core tidyverse packages? Load them in the chunk below:

``` r
# I've already installed the tidyverse package(s) on this server
# So all you need to do is load it
# install.packages("tidyverse")
library("tidyverse")
```

    ## Warning: package 'tidyverse' was built under R version 3.6.3

    ## -- Attaching packages --------------------------------------- tidyverse 1.3.1 --

    ## v ggplot2 3.3.5     v purrr   0.3.4
    ## v tibble  3.1.1     v dplyr   1.0.6
    ## v tidyr   1.1.3     v stringr 1.4.0
    ## v readr   1.4.0     v forcats 0.5.1

    ## Warning: package 'tibble' was built under R version 3.6.3

    ## Warning: package 'tidyr' was built under R version 3.6.3

    ## Warning: package 'readr' was built under R version 3.6.3

    ## Warning: package 'purrr' was built under R version 3.6.3

    ## Warning: package 'dplyr' was built under R version 3.6.3

    ## Warning: package 'forcats' was built under R version 3.6.3

    ## -- Conflicts ------------------------------------------ tidyverse_conflicts() --
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

Good job! You'll need to reload your packages every time you begin a new notebook.
