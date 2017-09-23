+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Katherine Mansfield R Package"

# Project summary to display on homepage.
summary = "katherinemansfieldr: an R package containing the collected works of Katherine Mansfield and text parsing functions for textual data analysis."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "katherinemansfield.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["R packages", "text mining"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
+++
## An R Package for Katherine Mansfield's Short Stories

> "I imagine I was always writing. Twaddle it was, too. But better far write twaddle or anything, anything, than nothing at all."

 *- Katherine Mansfield*

* On [GitHub](https://github.com/Amherst-Statistics/katherinemansfieldr)

This package allows users to access the short story works of Katherine 
Mansfield available on the ebooks@adelaide.edu website. The works have been converted from the UTF-8 text into files that are immediately ready for use. Each text is a character vector with elements that represent every paragraph. The works contained are as follows:

`somethingChildish` - *Something Childish, and Other Stories*, published in 1924 and contains stories from 1908 to 1921 

`bliss` - *Bliss, and Other Stories*, published in 1923 and contains stories from 1915 to 1920

`gardenParty` - *The Garden Party, and Other Stories*, published in 1922 and contains stories from 1920 to 1922

There is also `mansfieldComplete` which contains all of the stories from the three story collections in one character vector.

This package also contains text mining and feature extraction functions for textual data analysis problems. Tasks performed by functions contained in this package include:

* Parsing textual elements such as tokens (words), types (unique words), sentences and punctuation marks from a character vector of text

* Breaking large texts into chapters and subsections

* Extracting information about textual elements in the text such as frequency of words/punctuation marks, type/token ratio, and length of words/sentences

## Installation

To install this package, please refer to the following commands: 

```
devtools::install_github("Amherst-Statistics/katherinemansfieldr")
library(katherinemansfieldr)
```