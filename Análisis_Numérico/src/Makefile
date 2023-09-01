all: baragatti esquema_complejos caratula

portafolio1:
	latexmk -pdf -auxdir=./ -outdir=../ Portafolio N°1.tex
practica:
	latexmk -pdf -auxdir=./ -outdir=../ practica.tex
caratula:
	latexmk -pdf -auxdir=./ -outdir=../ caratula.tex
baragatti:
	latexmk -pdf -auxdir=./ -outdir=../ Complejos_Baragatti.tex
esquema_complejos:
	latexmk -pdf -auxdir=./ -outdir=../ Esquema_de_Contenidos.tex

.PHONY:clean
clean:
	rm *.log *.fls *.aux *.pdf *.synctex.gz *.fdb_latexmk *.out
