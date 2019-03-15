all: rdgroup20190315.pdf

clean:
	rm -f *.aux *.log *.nav *.out *.snm *.toc *.vrb
	rm -f rdgroup20190315.pdf

.PHONY: clean

rdgroup20190315.pdf: rdgroup20190315.tex
	pdflatex rdgroup20190315.tex
	pdflatex rdgroup20190315.tex
