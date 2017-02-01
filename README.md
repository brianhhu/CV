# CV
Personal CV in LaTeX

The CV is based loosely on a template from Jason Blevin's [website](http://jblevins.org/projects/cv-template/).

The bibentry package is a little weird- you have to compile the tex file with the \bibliography command at the end of the file in order to generate the appropriate .bbl file. Once this is generated, you can comment out the \bibliography command to only generate the in-text references.

**hucv** is a .bib file with entries for each of my publications. This has to be updated manually for new publications.

**myabbrvnat** is a custom .bst file which supports bibliography entries which do not have yet have a publication date (e.g. articles that have been submitted, in preparation, etc)
