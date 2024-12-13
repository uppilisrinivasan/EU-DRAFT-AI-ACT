all: compile

compile:
	pdflatex template
	bibtex template
	pdflatex template
	pdflatex template

view:
	open template.pdf

clean:
	rm *.blg *.bbl *.aux *.log template-blx.bib *.bcf *.xml