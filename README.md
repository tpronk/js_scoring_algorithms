# Introduction
Examples of scoring algorithms of cognitive tasks in JavaScript (JS). They make heavy use of three JS functions ([map, filter, reduce](https://www.freecodecamp.org/news/javascript-map-reduce-and-filter-explained-with-examples/)) to perform array operations similar to those often used in R and NumPy.

# How to use
Below are three ways you could try out an example
1. Clone this repo, install [node](https://nodejs.org/en/) and run `node <example_file.js>` inside of the repo directory
2. Copy-paste the contents of an example into the [browser console](https://appuals.com/open-browser-console/)
3. Include an example in an HTML page

# Overview of examples
## vpt_diff_of_means.js
This example calculates a "VPT Difference of Means score", as described in [this splithalfr vignette](https://rdrr.io/cran/splithalfr/f/inst/doc/vpt_diff_of_means.Rmd). The example dataset is from UserID 23 in the ds_vpt dataset of the splithalfr R-package, which is also used as a [splithalfr unit test](https://github.com/tpronk/splithalfr/tree/main/tests).
