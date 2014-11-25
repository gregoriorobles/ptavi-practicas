# $Id: makefile 4068 2006-05-25 13:22:42Z jjamor $

all: pdf
	echo "pfinal created in PDF format"

pdf: pfinal.tex
	pdflatex pfinal.tex; pdflatex pfinal.tex


html: pfinal.tex
	rm -rf html; mkdir html; latex2html -dir html pfinal.tex

clean:
	rm -f pfinal.dvi pfinal.ps pfinal.pdf kk.* *aux *~ *idx *blg *log *toc *bbl *out *lof *lot */*aux */*~

