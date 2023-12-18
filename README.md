thesis-template
===============

LaTeX template for a PhD, Master's or Bachelor's thesis, or actually any kind of thesis.
This is a minimalistic version of my own PhD thesis, whose source files are fully available in [this repository](https://github.com/cyrraz/phd-thesis).

The pdf of the thesis can be produced by running `make`.
For the creation of the pdf file, you need a distribution of TeX, such as [TeX Live](https://www.tug.org/texlive/quickinstall.html).
An alternative is to use an online LaTeX editor, such as [Overleaf](https://www.overleaf.com/).

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

See also
--------
* [phd-thesis](https://github.com/cyrraz/phd-thesis):  PhD thesis in Particle Physics written in LaTeX.
* [cv-template](https://github.com/cyrraz/cv-template): Template for a CV/resume in LaTeX.
* [letter-template](https://github.com/cyrraz/letter-template):  Very simple template for a letter in LaTeX.
* [particle-physics-presentations](https://github.com/cyrraz/particle-physics-presentations): Public presentations in Beamer LaTeX given during my PhD and postdoctoral studies in Particle Physics.
* [moriond-2023-proceedings-ewp-radiative](https://github.com/cyrraz/moriond-2023-proceedings-ewp-radiative): Proceedings for my talk at the Moriond conference.
