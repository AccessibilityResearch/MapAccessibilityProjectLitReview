.PHONY: all build run clean

all: build

build:
	#!/bin/bash
	> main.bib
	cat ./christian/christian.bib >> main.bib
	echo "" >> main.bib
	cat ./Aaron/aaron.bib >> main.bib
	echo "" >> main.bib
	cat ./karter/karter.bib >> main.bib

clean:
	rm main.bib