# Indiana University Bloomington - Thesis Template

*Indiana University Bloomington*

*Liang Chen*

*Music Informatics Ph.D.*

*2018*

This is a thesis template that meets the [official dissertation formatting requirements](https://graduate.indiana.edu/thesis-dissertation/formatting/doctoral.html) from Indiana University Bloomington.

# Usage of the Template

1. Open the "titePage.tex" file, and input your information in the designated section.
2. Open the "approvalPage.tex" file, and input your information in the designated section.
3. Open the "dedication.tex", "acknowledgments.tex", "abstract.tex", and "vita.tex" pages and enter your information.
4. Open the "references.tex" file, and input your citations, in BiBTeX format.

After these steps are complete, the main content of the thesis can be entered into the various "chapter<#>.tex" files, along with any appendices in the "appendix.tex" file.

To compile the template, using your preferred TeX editor, run the following commands in sequence:

1. pdflatex thesis.tex
2. bibtex thesis.aux
3. pdflatex thesis.tex
4. pdflatex thesis.tex
