# Brian Hu's Personal CV in LaTeX

This CV is based loosely on a LaTeX template from [Jason Blevins' website](http://jblevins.org/projects/cv-template/).

**hucv** is a .bib file with BibTeX entries for each of my publications. This has to be updated manually for new publications.

**myabbrvnat** is a custom .bst file which supports bibliography entries which do not yet have a publication date (e.g. articles that have been submitted, in preparation, etc)

** OLD **
The bibentry package is a little weird- you have to first compile the tex file with the \bibliography command in order to generate the appropriate .bbl file. However, this will also add a list of references to the end of the CV (which is not ideal). Once this .bbl file has been created, you can simply comment out the \bibliography command and re-compile the tex file to have the in-text references appear only at the appropriate location within the CV.
