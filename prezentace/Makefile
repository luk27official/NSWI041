all: review.pdf

review.pdf: review.tex
	pdflatex $<

clean:
	rm -f *.aux *.log *.nav *.out *.snm *.toc
	rm -f review.pdf
