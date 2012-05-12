# Définition des Macros :
BASENAME = rapport
FIGURE = 
LATEX = pdflatex
DVItoPDF = dvipdf
DPFLAGS = 
VIEWER = xdvi
PDFVIEWER = open
IMG = ./fig2dev
EPSFLAGS = -L eps

.PHONY: openPdf clean

# Ceci est notre makefile pour la génération de fichier LaTeX
all : openPdf

openPdf : $(BASENAME).pdf
	$(PDFVIEWER) $<

$(BASENAME).pdf : $(BASENAME).tex
	$(LATEX) $<


# Suppression des fichiers intermédiaires
clean : 
	rm *.aux *.log





