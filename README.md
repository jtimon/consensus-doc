# Description:

Document with pictures for planning libconsensus completion.

## Dependencies:

texlive
emacs
plantuml
java
graphviz

## Generate images:

java -jar ~/path/to/plantuml.8048.jar ./plantuml/*

## Generate document:

emacs --batch --visit=libconsensus.org -f org-latex-export-to-pdf
