all: review.pdf

review.pdf: review.tex
	pdflatex $<

clean:
	rm -f *.aux *.log *.nav *.out *.snm *.toc

distclean: clean
	rm -f review.pdf
