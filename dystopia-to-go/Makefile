default:
	xelatex --halt-on-error dystopia.tex > /dev/null

alert: 
	xelatex --halt-on-error dystopia.tex 

print:
	make default
	pdflatex --halt-on-error print.tex

clean:
	rm -rf *~ *aux *log 
