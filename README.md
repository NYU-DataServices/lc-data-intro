# Library Carpentry: Introduction to Working with Data (Regular Expressions)

This repository houses an adaption of the Library Carpentry lesson, [Introduction to Working with Data (Regular Expressions)](https://librarycarpentry.org/lc-data-intro/), edited and reformatted into a [bookdown](https://www.bookdown.org/) book.

## Build this book locally
1. Fork, clone or download this project
2. Install R & RStudio
3. Install the bookdown, RMarkdown, and tinytex packages in RStudio with the following two commands in the R console:
	* `install.packages(c("rmarkdown", "bookdownplus")`

You can also click `Tools > Install Packages` and type the package names (make sure "install dependencies" is checked) separated by commas.

4. Go to the project folder and double click `lc-data-intro.Rproj` to start RStudio
5. Run this command in the R Console after RStudio opens: `bookdown::render_book('index.Rmd', 'all', , output_dir = 'docs')`
6. Go to the folder `docs/` in the project folder and click `index.html` to view the book locally in your browser.

## Contact info
You are welcome to email me at [vicky dot steeves at nyu dot edu](mailto:vicky.steeves@nyu.edu) if you have questions or concerns, or raise an issue on this repository and I will do my best to respond quickly!
