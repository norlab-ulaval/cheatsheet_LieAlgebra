# Lie Algebra Cheatsheet
Inspired from 'State Estimation for Robotics' by Tim Barfoot and a lot of Lie algebra courses found online.

The aim is to regroup all the basic notions of Lie Algebra in one place, as there is a lot of notations to remember!

Also, check [Tim Barfoot's website](http://asrl.utias.utoronto.ca/~tdb/) for
* the pdf version of the book 
* a cheatsheet of all useful identities of Lie groups, algebras and jacobians.

Feel free to suggest and add other notions that you feels necessary for a basic understanding of the field!

To compile and generate the png version, install `latexmk` and `pdftoppm` then run
```bash
latexmk main
```
Or if you do not want to use `latexmk`, run
```bash
pdflatex main.tex; pdftoppm -png main.pdf preview
```
