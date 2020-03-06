# wRite your paper with R Markdown
This is the material for the hands-on workshop that will introduce you to R Markdown and teach you how to impress future collaborators with the skills to produce (and reproduce) papers containing your complex computing code, eloquently written text, perplexing math equations, and funny images - all in the same document!

## Instructions
To run this example you will need to install [rmarkdown](https://cran.r-project.org/web/packages/rmarkdown/index.html) and [knitr](https://cran.r-project.org/web/packages/knitr/index.html) `install.packages(c('rmarkdown', 'knitr'))`. We need knitr to do  nice formating of tables. You can then open `gender.rmd` and press the knit button to render the markdown document.

## Data for the day
In this example we will be looking at topical subject, which is [gender differences across UCL departments](https://www.ucl.ac.uk/srs/student-statistics). Are you courious to see which departments are most gender diverse?
We will compare the latest figures with those for when this example was first used back in 2016-2017. 
The data is provided in PDF format which is a bit anoying and needs to be converted to tables, since a copy past does is not good enough for this, we used the online tool [PdfToTables](https://pdftables.com/) for the conversion. But all the converted data you will need is available in data folder of this repository.

# Markdown Resources
- [Cheat Sheet](https://rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf)
- [Documentation](https://rmarkdown.rstudio.com/docs/)
- [Gallery](https://rmarkdown.rstudio.com/gallery.html)

# Other resources
- [pdftotables - convert pdf tables to csv/xlsx](https://pdftables.com/)
- [TeXMed - a BibTeX interface for PubMed](https://www.bioinformatics.org/texmed/)
- [Mathematics in R markdown](https://www.calvin.edu/~rpruim/courses/s341/S17/from-class/MathinRmd.html)
- [cite - an RStudio addin to insert BibTex citation in Rmarkdown documents](https://cran.r-project.org/web/packages/Cite/index.html)
- [Github - repo of citation style formats](https://github.com/citation-style-language/styles)
