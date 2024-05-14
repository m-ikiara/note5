PDFTeX := pdflatex
TeXSRC := main.tex

.PHONY: all clean

all: target

target: $(TeXSRC) $(BibTeXSRC)
	$(PDFTeX) $(TeXSRC)

clean:
	rm -f target
