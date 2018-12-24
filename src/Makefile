all: pdf

pdf:
	pdflatex thesis.tex
	bibtex thesis
	pdflatex thesis.tex
	pdflatex thesis.tex

clean:
	rm -f *.log *.aux *.lof *.lot *.toc *.bbl *blx.bib *.out *.blg *.run.xml
