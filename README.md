# kohl2015latex
Latex version of Current Opinion article written by Kohl, Huoviala and Jefferis.

## compile
You should be able to compile by running `make` in the source directory.  
This is known to work with pdflatex supplied by [MacTex2014](https://tug.org/mactex/).

## notes
This document uses only *standard* latex and can be compiled with `pdflatex`. The only peculiarity is that we have used `biblatex` for the convenience of generating
annotated bibliographies. If necessary it should be possible to switch to classic `bibtex`
using a style like `annotate.bst`. See e.g.

* <http://tex.stackexchange.com/questions/100594/annotated-bibliography>
* <http://math.ucdenver.edu/~billups/courses/ma5779/annotated_bibliography.html>