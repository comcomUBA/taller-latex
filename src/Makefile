
TEX = clase
 
$(TEX).pdf:
	pdflatex -shell-escape $(TEX).tex

.PHONY: clean
clean:
	rm -f *.pdf *.aux *.nav *.snm *.log *.out *.toc *.synctex.gz
