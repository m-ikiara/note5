PDFTeX := pdflatex
TeXFLAGS := --pdf
TeXSRC := main.tex

.PHONY: all clean

all: target

target: $(TeXSRC) $(BibTeXSRC)
	$(PDFTeX) $(TeXFLAGS) $(TeXSRC)

clean:
	rm -f target
