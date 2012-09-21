report:
	pdflatex -synctex=1 -interaction=nonstopmode report.tex

bib:
	bibtex report.aux
	
all:
	pdflatex -synctex=1 -interaction=nonstopmode report.tex
	bibtex report.aux
	pdflatex -synctex=1 -interaction=nonstopmode report.tex
	pdflatex -synctex=1 -interaction=nonstopmode report.tex
	
clean:
	rm -f *.pdf *.bbl *.aux *.blg *.toc *.gz chapters/*.aux
