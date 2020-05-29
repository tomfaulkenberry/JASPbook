TEX=pdflatex
BIB=biber

lsj.pdf: ../tex/*.tex ../data/*
	$(TEX) lsj
	$(BIB) lsj
	$(TEX) lsj
	$(TEX) lsj

clean:
	$(RM) lsj.{aux,bbl,bcf,blg,log,out,run.xml,toc}
