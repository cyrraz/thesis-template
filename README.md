LaTeX template for a PhD, Master's or Bachelor's thesis, or actually any kind of thesis.
This is a minimalistic version of my own PhD thesis, whose source files are fully available in [this repository](https://github.com/cyrraz/phd-thesis).

The pdf of the thesis can be produced by running `make`.
For the creation of the pdf file, you need a distribution of TeX, such as [TeX Live](https://www.tug.org/texlive/quickinstall.html).

The main files and folders are:
* `thesis.tex`: main tex file whose purpose is to import all the other tex files;
* `Makefile`: makefile to produce the pdf of the thesis;
* `figs/`: folder containing the figures;
* `tables/`: folder containing the tables;
* `chapters/`: folder containing the tex files of the thesis chapters;
* `include/packages.tex`: file listing the used packages;
* `include/styles.tex`: file defining the style of the thesis;
* `include/definitions.tex`: file defining new commands/shortcuts;
* `include/bibliography.bib`: file containing BibTeX entries, which can be maintained with [JabRef](https://www.jabref.org/);

