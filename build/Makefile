TEX=pdflatex
BIB=biber

lsj.pdf:
	$(TEX) lsj
	$(BIB) lsj
	$(TEX) lsj
	$(TEX) lsj

tidy:
	$(RM) lsj.{aux,bbl,bcf,blg,log,out,run.xml,toc}

clean: tidy
	$(RM) lsj.pdf
