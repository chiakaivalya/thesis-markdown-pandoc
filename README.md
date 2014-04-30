thesis-markdown-pandoc
======================

A template for creating a PhD thesis in markdown + pandoc

Run this pandoc command to build your pdf:

```
pandoc --latex-engine=xelatex -H preamble.tex -V fontsize=12pt -V documentclass:book -V papersize:a4paper 
-V classoption:openright --chapters --bibliography=papers.bib --csl="csl/nature.csl" title.md summary.md
zusammenfassung.md acknowledgements.md toc.md "introduction/intro1.md" "introduction/intro2.md" chapter2_paper.md
chapter3_extra_results.md chapter4_generaldiscussion.md appendix.md references.md -o "phdthesis.pdf"

```

[Preview the result](https://www.dropbox.com/s/nl7a2n6khdg8m4p/phdthesis.pdf)


[Corresponding blog article](http://chiakaivalya.wordpress.com/2014/04/23/using-markdown-pandoc-to-write-my-biology-phd-thesis/)
