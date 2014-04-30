cd /Users/chia/Dropbox/ThesisMarkdownPandoc

pandoc  --latex-engine=xelatex -H  preamble.tex -V fontsize=12pt -V documentclass:book -V papersize:a4paper -V classoption:openright --chapters --bibliography=papers.bib --csl="csl/nature.csl"  title.md summary.md zusammenfassung.md acknowledgements.md toc.md "introduction/intro1.md" "introduction/intro2.md"   chapter2_paper.md chapter3_extra_results.md chapter4_generaldiscussion.md appendix.md references.md  -o "phdthesis.pdf"
  