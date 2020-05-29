# Building the file from scratch

This is a complex file, so building will take a little patience. It is assumed that you will have a full working LaTeX package installed on your machine. 

Here are the rough steps involved:

1. make sure the build directory contains *only* the `lsj.tex` file (and optionally the `lsj.pdf` file -- not needed in the build). 
2. in your terminal, run `pdflatex lsj` -- there will be a lot of errors for missing references during the first run.
3. run `biber lsj` -- this will add the references in!
4. run `pdflatex lsj` again -- this should build a PDF, but it won't be correct yet. Scroll up in your terminal output a bit and make sure there's no message about needing to run LaTeX again to fix page breaks.
5. run `pdflatex lsj` one more time

