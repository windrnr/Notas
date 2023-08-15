all: baragatti esquema_complejos caratula

caratula:
	latexmk -pdf -auxdir=./ -outdir=../ caratula.tex
baragatti:
	latexmk -pdf -auxdir=./ -outdir=../ Complejos_Baragatti.tex
esquema_complejos:
	latexmk -pdf -auxdir=./ -outdir=../ Esquema_de_Contenidos.tex

.PHONY:clean
clean:
	rm *.log *.fls *.aux *.pdf *.synctex.gz *.fdb_latexmk *.out
