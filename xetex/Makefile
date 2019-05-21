.PHONY: fig

TEX = xelatex
BIB = bibtex

PAPER = main
CHAPS = chap/chap1.tex


$(PAPER).pdf: $(PAPER).tex $(CHAPS) fig
	$(TEX) $(PAPER)
	$(TEX) $(PAPER)

fig: $(MPFIGS)
	$(MAKE) -C fig
