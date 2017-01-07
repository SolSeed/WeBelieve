We Believe
==========

This is the source for the hardcover book that is [available to purchase with zero markup](http://www.lulu.com/shop/brandon-sanders/we-believe/hardcover/product-21052027.html).  The free electronic version [is also available](http://solseed.org/we_believe).

We Believe presents the [SolSeed](http://solseed.org/) Creed one verse at a time with commentary on each verse.

## Contributing
### Pre-requisites

Go to http://www.latex-project.org/get/ and get `latex` for your system.

### Building the Book

#### First Time (or after editing `webelieve.bib`)
```sh
pdflatex main  # creates the main.aux file
bibtex main    # creates main.blg and main.bbl
pdflatex main  # take stock of all the citations and references
pdflatex main  # render pdf will a citations in place
open main.pdf
```

#### After an edit of `main.tex`

```sh
pdflatex main
```
