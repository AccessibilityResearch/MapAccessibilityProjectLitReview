.PHONY: all build run clean

all: build run

build:
	pdflatex main.tex
	bibtex main
	pdflatex main.tex
	pdflatex main.tex

run:
	open main.pdf

clean:
	find . -type f -print | grep -E '^./main.(aux|bbl|blg|log|out)$$' | xargs rm