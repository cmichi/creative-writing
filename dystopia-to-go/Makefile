default:
	xelatex --halt-on-error dystopie.tex > /dev/null

alert: 
	xelatex --halt-on-error dystopie.tex 

print:
	make default
	pdflatex --halt-on-error print.tex

clean:
	rm -rf *~ *aux *log 
