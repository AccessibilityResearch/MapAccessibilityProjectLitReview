.PHONY: all build run windows clean docker

all: run

build:
	docker build -t lit .
	docker create --name lit lit

run:
	docker run -v $(PWD):/app lit /bin/bash -c "make docker && find . -type f -print | grep -E '^./main.(aux|bbl|blg|log|out)$$' | xargs rm"

windows:
	docker run -v ${PWD}:/app lit /bin/bash -c "make docker && find . -type f -print | grep -E '^./main.(aux|bbl|blg|log|out)$$' | xargs rm"


clean:
	docker rm lit

docker:
	pdflatex main.tex
	bibtex main
	pdflatex main.tex
	pdflatex main.tex