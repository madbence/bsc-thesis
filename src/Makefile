simple:
	xelatex -shell-escape diploma.tex

full: clean
	xelatex -shell-escape diploma.tex
	bibtex diploma.aux
	xelatex -shell-escape diploma.tex
	xelatex -shell-escape diploma.tex

clean:
	rm *.toc *.aux *.thm *.log *.blg *.bbl *.out *.pdf || true
