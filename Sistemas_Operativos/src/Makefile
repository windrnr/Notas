


all: memoria introducción

memoria:
	latexmk -pdf -auxdir=./ -outdir=../ Gestión_de_la_Memoria.tex

introducción:
	latexmk -pdf -auxdir=./ -outdir=../ Introducción.tex

.PHONY: clean
clean:
	rm *.log *.fls *.aux *.pdf *.synctex.gz *.fdb_latexmk *.out *.ind *.idx *.ilg *.toc
