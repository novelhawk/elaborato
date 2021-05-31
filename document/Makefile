build/main.pdf: content/** images/** *.tex *.bib
	latexmk -interaction=nonstopmode -pdf -output-directory="build" -bibtex main.tex

.PHONY: watch
watch:
	latexmk -interaction=nonstopmode -pdf -output-directory="build" -bibtex -pvc -view=none main.tex

