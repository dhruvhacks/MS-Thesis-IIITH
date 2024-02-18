# MS-CSE Thesis by Dhruv Srivastava

## Steps to compile the thesis locally (Ubuntu)
1. Install TexLive <br>
`$ sudo apt-get install texlive-latex-base texlive-fonts-recommended texlive-fonts-extra texlive-latex-extra`

2. Compile the thesis using `pdflatex` <br>
`$ pdflatex main.tex`

(Miscellaneous step)
Re-generate the `main.bbl` file if you make changes to `Bibliography/main.bib`. <br>
Execute the following commands/sequence to update the `.bbl` file and use updated references in compiled pdf.
```
$ pdflatex main.tex
$ bibtex main
$ pdflatex main.tex
$ pdflatex main.tex
```
