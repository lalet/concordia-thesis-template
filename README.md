[![DOI](https://zenodo.org/badge/106060364.svg)](https://zenodo.org/badge/latestdoi/106060364)
[![Build Status](https://travis-ci.org/lalet/concordia-thesis-template.svg?branch=master)](https://travis-ci.org/lalet/concordia-thesis-template)

## Concordia University LaTeX Template for Master's thesis or PHD thesis.
-------------------------------------------------------------------------

This is a LaTeX template for Master's thesis or PHD thesis, derived from official template of Concordia University, Montreal, Canada.
<iframe src="https://goo.gl/ajbvvW" width="100%" height="100%"></iframe>  
Steps to get started:
- Clone the repo ( `git clone https://github.com/lalet/concordia-thesis-template.git`)
- Make structural changes in `cuthesis_masters.tex` file.
- Define your constants such as thesis author, department, etc in `constants.tex` file.
- If you want to add new packages or define new styles, change them in `config.tex`.
- Each chapters have their own folders, so you can modify them separately in their own folders.

To build pdf, open `cuthesis.tex` in [TexMaker](http://www.xm1math.net/texmaker/) and build it.

## How to generate the pdf from command line 
0. Install ```pdflatex``` and ```bibtex```
1. Compile the document: ```pdflatex cuthesis; pdflatex cuthesis``` (yes, twice).
2. Generate the bibliography: ```bibtex cuthesis; pdflatex cuthesis``` (yes, once again).

Modify `.gitignore` according to your requirements.

Find the pdf sample at [PDF](https://github.com/lalet/concordia-thesis-template/releases)

Source : https://github.com/raxityo/concordia-latex-template
