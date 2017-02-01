# Brian Hu's CV
Personal CV in LaTeX

This CV is based loosely on a LaTeX template from Jason Blevins' [website](http://jblevins.org/projects/cv-template/).

The bibentry package is a little weird- you have to compile the tex file with the \bibliography command in order to generate the appropriate .bbl file. However, this will also add a list of references to the end of the CV (which is not ideal). Once this .bbl file has been generated, you can simply comment out the \bibliography command to only generate the in-text references at the appropriate location within the CV.

**hucv** is a .bib file with BibTeX entries for each of my publications. This has to be updated manually for new publications.

**myabbrvnat** is a custom .bst file which supports bibliography entries which do not yet have a publication date (e.g. articles that have been submitted, in preparation, etc)
