TeXSRC := main.tex
AuxSRC := main.aux

.PHONY: all clean

all: target

target: $(TeXSRC) $(AuxSRC)
	pdflatex $(TeXSRC) && bibtex $(AuxSRC) && pdflatex $(TeXSRC) && pdflatex $(TeXSRC)
clean:
	rm -f target
