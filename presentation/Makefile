
all : compile clean

compile :
	latexmk -pdf $(shell find *.tex -type f)

clean :
	rm -f *.log
	rm -f *.out
	rm -f *.synctex.gz
	rm -f *.fls
	rm -f *.aux
	rm -f *.fdb_latexmk