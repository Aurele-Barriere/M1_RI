# LaTeX Makefile
FILE=TD4

all: $(FILE).pdf

.PHONY: clean
clean:
	\rm *.aux *.blg *.out *.bbl *.log

$(FILE).pdf: $(FILE).tex
	pdflatex $(FILE)
	pdflatex $(FILE)
