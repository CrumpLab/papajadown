# papajadown

**NOTE:** This is a defunct example. See `vertical` for an improved and expanded version <https://crumplab.github.io/vertical/>

This is a template and minimal example for using papaja and pkgdown to share the results of a research project on the web. papaja is used to write an APA style manuscript. pkgdown is used to create a website from an R package. Putting the two together let's you share the APA paper in the form of a pkgdown website. This has the added benefit of being able to share the whole project as an R package, along with data (and pretty documentation for the data), and any custom functions used for analysis.

Documentation for functions and data appear in the reference tab, and the APA article appears (web-version) in the articles tab. This is a very minimal example with no addedd customization. The website produced by pkgdown can be further customized with some tweaking.

## The rundown

1. Make a new R project in R-studio, choose new R package
2. Make a vignettes folder, make a new papaja template .rmd file in that folder and write your APA paper
3. create a data folder, but your .RData files in that folder
4. write documentation for the data files in the R folder, using roxygen2
5. build the website using pkgdown `pkgdown::build_site()
6. Everything gets compiled into a docs folder, share the website on github using github pages (which serves the content in the docs folder).

The source files are located in this github repository [https://github.com/CrumpLab/papajadown](https://github.com/CrumpLab/papajadown)

If you are seeing this from the github repo, then the website is [https://crumplab.github.io/papajadown/](https://crumplab.github.io/papajadown/)

## Try this out

1. Fork the repo, or download it
2. Open the .rProj file in R-studio
3. Make sure `papaja`, `roxygen2`, and `pkgdown` libraries are installed
4. run `pkgdown::build_site()` in the console. This should build the website.
5. Modify the .rmd file in the vignette folder to change the APA paper. 
6. Modify everything in this repo to change it to things you want to say.


Note: this example is in development, but the basics seem to work. Will improve over time.
