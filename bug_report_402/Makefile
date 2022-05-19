PAPER = bug_report 
TEX = $(wildcard *.tex)
FIGS = $(wildcard figures/*.pdf figures/*.png graphs/*.pdf graphs/*.png)

default:
	echo $(FIGS)
	pdflatex $(PAPER)
	bibtex $(PAPER)

clean:
	rm -f *.aux *.bbl *.blg *.log *.out $(PAPER).pdf
